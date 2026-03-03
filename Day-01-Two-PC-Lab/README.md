Day 1 – Direct PC-to-PC Communication Lab

Objective: 
Configure direct communication between two PCs using static IP addressing in Cisco Packet Tracer.

Topology:
PC1 → PC2 (direct connection)

Configuration:

PC1
IP: 192.168.1.10
Subnet Mask: 255.255.255.0

PC2
IP: 192.168.1.11
Subnet Mask: 255.255.255.0

Verification:
1. Used ICMP (ping) to confirm connectivity.
2. Sent packet

Failure Testing Performed:

• Tested mismatched IP ranges (192.168.1.10 and 10.0.0.5)
• Observed failed connectivity due to different network IDs
• Identified need for router when devices are on separate networks

Key Takeaways:

Devices on the same subnet communicate directly at Layer 2.
Devices on different subnets require a Layer 3 device (router).
Subnet masks determine network boundaries.

Screenshots To Upload:

Packet Tracer topology view
IP configuration window for both PCs
Successful ping result
