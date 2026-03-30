# Simple-WAN-Interconnection-
<img width="1910" height="834" alt="Screenshot 2026-03-29 211107" src="https://github.com/user-attachments/assets/70104134-bd29-42ec-ad6e-acd8df887721" />

This project demonstrates a basic Wide Area Network (WAN) design that connects two geographically separated Local Area Networks (LANs) using Cisco routers.

The topology consists of two routers connected via a point-to-point link, simulating a WAN connection between two remote sites. Each router is connected to a local switch, which in turn connects multiple end devices such as PCs, laptops, and printers.

🔧 Key Features
WAN connectivity using point-to-point IP addressing (/30 subnet)
Two separate LANs with different IP subnets
Static routing configuration for inter-network communication
End-to-end connectivity between devices across both sites
🌐 Network Design
Router-to-Router connection using GigabitEthernet interfaces
LAN segmentation:
Site 1: 192.168.10.0/24
Site 2: 192.168.20.0/24
WAN network:
10.0.0.0/30
🎯 Objectives
Establish communication between two remote networks
Implement routing between LANs via WAN
Understand basic network design and IP addressing
Practice troubleshooting and connectivity verification
🧪 Testing
Successful ping between routers over WAN
Successful communication between devices in different LANs
