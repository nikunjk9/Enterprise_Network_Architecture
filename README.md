# **Enterprise-Network-Architecture**
The rapid evolution of networking technologies necessitates innovative approaches to address the dynamic requirements of modern organizations. This research project investigates the benefits and challenges of Software-Defined Networking (SDN) and proposes a comprehensive framework for dynamic network management. 

## **Introduction**
**Alkashaf Consultant (Private) Limited**, a consultant company with six major departments, served as the backdrop for this study.The company faced security vulnerabilities and network inefficiencies due to the absence of virtual local area networks (VLANs), security systems, Domain Name System (DNS) servers, Dynamic Host Configuration Protocol (DHCP) servers, File Transfer Protocol (FTP) servers, and robust backup systems. The aim of the project was to design and develop a network system using Cisco Packet Tracer, addressing these challenges. Through an in-depth exploration of various network technologies and security methods, the project identified the significance of virtual local area networks, inter-VLAN routing, dynamic host configuration protocol servers, the Open Shortest Path First (OSPF) routing protocol, and IPsec virtual private networks in ensuring seamless communication and data exchange. The proposed hierarchical architecture with redundancy at each layer increased network availability, while department-specific VLANs promoted safety and resource sharing. Inter-VLAN routing enhanced departmental communication, and dedicated DHCP servers optimized IP allocation, bolstering network security.
Integration of a File Transfer Protocol server streamlined file interchange, and a reliable backup system minimized the risk of data loss. The adoption of the Open Shortest Path First routing protocol facilitated dynamic route advertisement and traffic optimization. Security measures included Secure Socket Shell protocol, standard Access Control Lists, and Port Address Translation for Network Address Translation. Site-to-site IPsec virtual private networks were established to secure data transmission and enable remote communication. Upon implementation, the proposed network infrastructure and security system resulted in a significant enhancement of company activities. This research contributes to the understanding of SDN applications and provides valuable insights for organizations seeking dynamic and secure network management solutions.

## **Technologies Implemented**
1. Creating a network topology using `Cisco Packet Tracer`.
2. Hierarchical Network Design.
3. Connecting Networking devices with Correct cabling.
4. Configuring Basic device settings.
5. Creating `VLANs` and assigning ports VLAN numbers.
6. Creating both `data and voice VLANs` and assigning ports VLAN numbers.
7. Subnetting and `IP Addressing`.
8. Configuring `Inter-VLAN Routing` both on the Switches (SVI) and Routers (router-on-a-stick).
9. Configuring Dedicated DHCP Server device for Data to provide dynamic IP allocation.
10. Configuring Routers as `DHCP server` for Voice to provide IP Phones dynamic IP allocation.
11. Configuring `SSH` for secure Remote access.
12. Configuring `OSPF` as the routing protocol.
13. Configuring Standard `ACL` for VTY interfaces to restrict remote Access using SSH.
14. Configuring Port Address Traslations or `PAT` for `NAT`.
15. Configuring Standard ACL for `PAT`.
16. Configuring `VoIP or Telephony service` configuration in all routers.
17. Configuring `site-to-site IPsec VPN` on the gateway routers.
18. Configuring `Standard ACL` for site-to-site IPsec VPN.
19. Host Device Configurations.
20. Test and Verifying Network Communication.





## Screenshot
### 1. Simulation
----
![Screenshot 2023-07-26 154009.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/DESIGN%20AND%20SIMULATION/Screenshot%202023-07-26%20154009.png)

### 2. Vlan routing config
----
![VLAN CONFIG.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/Configuration-SW/VLAN%20CONFIG.png)

### 3. Configuration- Multi-Layer Switches
----
![IP-config SW2.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/Configuration-%20MLSW/IP-config%20SW2.png)

### 4. Configuration- Switches (VLAN CONFIG)
----
![VLAN CONFIG.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/Configuration-SW/VLAN%20CONFIG.png)

### 5. Dynamic Host Configuration Protocol (DHCP) Configuration
----
![DHCP- CONFIG.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/DHCP-SERVER/DHCP-%20CONFIG.png)
![DHCP- CONFIG.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/DHCP-SERVER/DHCP-CONFIG.png)

### 6. Domain Name System (DNS) Configuration
----
![DNS-CONFIG.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/DNS-SERVER/DNS-CONFIG.png)

### 7. File Transfer Protocol (FTP) Configuration
----
![VLAN CONFIG.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/FTP-SERVER/FTP-CONFIG.png)

### 8. HQ-Router Configuration
----
![VLAN CONFIG.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/HQ-Router/NAT-CONFIG.png)

### 9. ISP-ROUTER Configuration
----
![VLAN CONFIG.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/ISP-ROUTER/Routing-config.png)

### 10. Server-side-Switch Configuration
----
![VLAN CONFIG.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/Server-side-SW/do%20show%20start.png)

### 11. VOICE-ROUTER Configuration
----
![VLAN CONFIG.png](https://github.com/nikunjk9/Enterprise_Network_Architecture/blob/master/VOICE-ROUTER/Ephones(1).png)
