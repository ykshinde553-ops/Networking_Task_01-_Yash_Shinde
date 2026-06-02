Networking Task 01: Understanding Your Network Environment
Name

Yash Shinde

Objective

The objective of this task is to understand the basic components of a computer network and identify the network configuration of my system.

Part A: Network Information
System Details
Parameter	Value
Hostname	kali
IPv4 Address	192.168.239.128
MAC Address	00:0c:29:52:9b:4e
Default Gateway	Not Available (Run ip route)
DNS Server	Not Available (Run cat /etc/resolv.conf)
Commands Used
hostname
ip addr
ip link

Screenshots of the command outputs are attached.

Part B: Basic Networking Concepts
1. What is an IP Address?

An IP (Internet Protocol) Address is a unique numerical address assigned to every device connected to a network. It helps devices communicate with each other over the Internet or a local network.

Example:
192.168.239.128

2. What is a MAC Address?

A MAC (Media Access Control) Address is a unique hardware identifier assigned to a network interface card (NIC). It is used for communication within a local network.

Example:
00:0c:29:52:9b:4e

3. What is a Default Gateway?

A Default Gateway is the router that forwards network traffic from a local network to external networks such as the Internet.

4. What is DNS?

DNS (Domain Name System) converts domain names such as google.com into IP addresses so that computers can locate websites.

5. Difference Between Public IP and Private IP
Public IP	Private IP
Accessible on the Internet	Used inside local networks
Assigned by ISP	Assigned by Router
Globally unique	Can be reused
Directly reachable	Not directly reachable
Part C: Basic Network Diagram
            Internet
                |
                |
         VMware Network
                |
            Router
                |
          Kali Linux VM
      IP: 192.168.239.128
      MAC: 00:0c:29:52:9b:4e
Part D: Network Connectivity Test
Commands
ping google.com
traceroute google.com
Was the ping successful?

Yes, the ping was successful if replies were received from google.com.

How many hops were shown?

The number of hops depends on the network path and ISP configuration. Check the traceroute output for the exact count.

What is the purpose of traceroute?

Traceroute identifies the path that network packets take from the source device to the destination server. It helps diagnose routing problems and network delays.

Conclusion

This task helped me understand important networking concepts such as IP Address, MAC Address, DNS, Default Gateway, Ping, and Traceroute. I also learned how to identify network configuration information on a Kali Linux system and understand how devices communicate over a network.

README Summary

This project involved identifying network configuration details from a Kali Linux virtual machine, understanding basic networking concepts, creating a network diagram, and performing connectivity tests using ping and traceroute commands.
