# City-Wide Corporate Network Design Using Cisco Packet Tracer

This project demonstrates the design and implementation of a cost-effective, scalable, and reliable city-wide network for three different companies (Company X, Y, and Z). The simulation was performed using **Cisco Packet Tracer**, utilizing hybrid topologies and dynamic routing protocols.

## 📌 Project Overview
The primary objective was to interconnect three independent organizations while maintaining their internal LAN structures. The design ensures optimal IP address utilization through custom subnetting and efficient inter-company communication using dynamic routing.

### Key Features:
* **Topology:** Hybrid model (Star topology for internal LANs and Bus topology for inter-router serial links).
* **Routing Protocol:** RIP version 2 (RIPv2) for dynamic route discovery.
* **IP Management:** Static IP assignment and custom Subnetting.
* **Connectivity:** Serial links used for wide-area connections between routers.

---

## 🛠️ Network Architecture & Design

### Company Specifications:
1. **Company X:** 5 rooms, 1 PC per room, utilizing 5 switches and 1 router.
2. **Company Y:** 3 rooms, 3 PCs per room, utilizing 3 switches and 1 router.
3. **Company Z:** 2 rooms, 4 PCs per room, utilizing 2 switches and 1 router.

### Subnetting Details:
* **Company X:** 144.186.96.0/19 (Custom subnets for 5 rooms).
* **Company Y:** 50.152.0.0/15 (Custom subnets for 3 rooms).
* **Company Z:** 210.98.169.64/26 (Custom subnets for 2 rooms).

---

## 🚀 Configuration Steps
1. **Planning:** Allocated unique IP blocks and calculated subnets for each company.
2. **Topology:** Placed and connected hardware (Routers, Switches, PCs) in Packet Tracer.
3. **Interface Setup:** Configured FastEthernet and Serial ports via CLI.
4. **Routing:** Enabled **RIPv2** on all routers to allow cross-company communication.
5. **Validation:** Conducted ping tests within LANs and across different company networks.

---

## ✅ Results
* **Internal Connectivity:** All PCs successfully communicated within their respective LANs.
* **Cross-Company Communication:** Verified successful pings between different companies (e.g., Company X to Company Z) after RIP propagation.
* **Efficiency:** The design achieved a functional city-wide network with minimal hardware requirements.

## 📂 Deliverables
* `.pkt` file: The complete Cisco Packet Tracer simulation.
* `City-Wide Corporate Network Design report.docx`: Detailed technical report covering design and analysis.

---
**Project by:** Shumaila Arif 
