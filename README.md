Scan Your Local Network for Open Ports

steps
1. Install Nmap
2. Open Nmap and give the ip address of your computer as target then it gives a command
3. Open command prompt run it as administrator and paste the command in it run the command
4. Now you can use the Nmap
5. check the subnet range of your system according to the range you have to take 24 bits of network prefix because the subnet range is 255.255.255.0
   It is CIDR notation there a different notations are there for different subnet ranges

                     CIDR Notation (Quick Reference):

            Subnet Mask	           CIDR      	    IPs in Range
            255.255.255.0          /24	              256
            255.255.0.0	           /16	              65,536
            255.255.255.128	     /25	              128

6. Run this command 192.168.1.0/24 in command prompt
7. Then you will get the data of portswhich are open,close and blocked
