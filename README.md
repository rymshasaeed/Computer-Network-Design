# Computer-Network-Design
This network simulation scenario is about designing a topology of a Local Area Network (LAN) for an organization in which various hosts of different departments would be set up so that they could interact and communicate with each other by interchanging data. A network, which connects various departments to each other, puts forward communication among different departments

## Objectives
The focus of this project is to design and simulate a computer network for an organization having 6 departments. Main objectives include,
- Understanding the advantages of using VLAN in a network
- Understanding that how broadcasting is controlled
- Subnetting a large network into smaller networks
- Configuring five departments for at least 50 users
- Configuring one department for variable number of users
- Designing the organization’s own webserver and its DNS

## Software Environment <img src="https://www.logolynx.com/images/logolynx/s_cc/cce4526c175bf2cc3f4908b8a6c4dd07.png" alt="Cisco Packet Tracer" width="5%"/>
<p align='justify'> Cisco Packet Tracer 7.3.0  has been used to design a systematic and well-planned topology, satisfying all the requirements. Packet Tracer is a cross-platform visual simulation program designed by Cisco Systems that allows users to create network topologies and imitate modern computer networks. The software allows users to simulate the configuration of Cisco routers and switches using a simulated command line interface. </p>

## Network Specifications
Local ISP has been assigned two Public IP addresses: `128.0.72.75` for internet access and `128.0.72.76` for organization webserver. The organization uses a private IP block `172.16.0.0` for internal IP address assignment to 5 departments. These five departments have at least 50 users while the sixth department has variable number of users and in future it would accommodate furthers users.
The designed network structure includes the following,
- Webserver for the organization
- DNS server for webserver, to translate the URL to IP address
- A single DHCP server for entire organization (DHCP server would be used for the department with variable number of users)
