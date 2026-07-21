# Enterprise Campus Network Simulation using Cisco Packet Tracer

## 📌 Overview

This project demonstrates the design and implementation of a scalable **Enterprise Campus Network** using **Cisco Packet Tracer**. The network simulates a real-world organizational infrastructure consisting of a Headquarters, a Branch Office, and a Cloud network connected through WAN links.

The project implements VLAN segmentation, inter-VLAN routing, centralized services, and hierarchical network design to provide secure and efficient communication between departments.

---

## 🏢 Network Architecture

The network consists of:

- Headquarters (HQ)
- Branch Office
- Cloud Network
- WAN Connectivity
- Department-based VLANs
- Centralized Servers

---

## 🖥️ Devices Used

| Device | Quantity |
|---------|---------:|
| Cisco 2911 Routers | 3 |
| Cisco 3560 Multilayer Switches | 2 |
| Cisco 2960 Access Switches | 10 |
| PCs | 10 |
| Printers | 10 |
| Servers | 3 |

---

## 🌐 Network Topology

- Headquarters Router
- Branch Router
- Cloud Router
- Multilayer Switches
- Access Switches
- Email Server
- Web Server
- FTP Server
- WAN Links

---

## 🏗️ Department VLANs

| VLAN | Department | Network |
|------|------------|----------------|
| 10 | Admin | 192.168.1.0/24 |
| 20 | Finance | 192.168.2.0/24 |
| 30 | HR | 192.168.3.0/24 |
| 40 | Business | 192.168.4.0/24 |
| 50 | Building B | 192.168.5.0/24 |
| 60 | Building B | 192.168.6.0/24 |
| 70 | Student Lab | 192.168.7.0/24 |
| 80 | IT Department | 192.168.8.0/24 |
| 90 | Branch Staff | 192.168.9.0/24 |
| 100 | Branch Students | 192.168.10.0/24 |

---

## 🌍 WAN Networks

| Connection | Network |
|------------|----------------|
| HQ ↔ Branch | 10.10.10.0/30 |
| HQ ↔ Cloud | 10.10.10.4/30 |
| Cloud Network | 20.0.0.0/30 |

---

## 🚀 Features

- Enterprise hierarchical network design
- VLAN segmentation
- Inter-VLAN routing
- WAN connectivity
- Centralized Email Server
- Web Server
- FTP Server
- Department-wise network isolation
- Branch office connectivity
- Printer connectivity
- Network scalability
- Cisco IOS configuration and verification

---

## 🛠️ Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- VLAN
- Inter-VLAN Routing
- Layer 2 Switching
- Layer 3 Switching
- WAN
- IPv4 Addressing
- Trunking
- Enterprise Network Design

---

## 📂 Project Structure

```
Enterprise-Campus-Network/
│
├── README.md
├── Enterprise_Campus_Network.pkt
├── topology.png
├── network-overview.png
├── vlan-design.png
├── hq-network.png
├── branch-network.png
└── screenshots/
```

---

## 📸 Screenshots

### Complete Network Topology

> Add your complete topology screenshot here.

```
images/topology.png
```

### Headquarters Network

> Add HQ screenshot.

### Branch Office

> Add Branch Office screenshot.

### VLAN Configuration

> Add VLAN verification screenshots.

### Routing Verification

> Add routing screenshots.

---

## 🔍 Verification Commands

```bash
show running-config
show ip interface brief
show ip route
show vlan brief
show interfaces trunk
show mac address-table
show spanning-tree
ping
traceroute
```

---

## 📈 Learning Outcomes

Through this project, I gained practical experience in:

- Enterprise network design
- VLAN implementation
- Inter-VLAN routing
- WAN connectivity
- Layer 2 and Layer 3 switching
- IP addressing and subnetting
- Cisco IOS configuration
- Network verification and troubleshooting
- Designing scalable campus networks

---

## 🎯 Future Improvements

- Implement OSPF dynamic routing
- Configure DHCP Server
- Add DNS Server
- Configure NAT/PAT
- Implement ACLs
- SSH remote management
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection
- Rapid PVST+
- EtherChannel

---

## 👨‍💻 Author

**Suhaib Rehaman**

Electronics & Communication Engineer | Networking & Cybersecurity Enthusiast

GitHub: https://github.com/suhiabrehaman2

LinkedIn: https://linkedin.com/in/suhaib-rehaman

---

## ⭐ If you found this project useful, consider giving it a Star!
