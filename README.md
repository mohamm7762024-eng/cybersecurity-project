# Cisco Packet Tracer Network Security Project

## Project Overview

This project was created using Cisco Packet Tracer to design and configure a secure network infrastructure.

The project demonstrates practical networking and network security concepts, including VLANs, DHCP, SSH, Port Security, ACLs, and Inter-VLAN Routing.

## Technologies Used

- Cisco Packet Tracer
- Cisco Routers
- Cisco Switches
- VLAN
- DHCP
- SSH
- Port Security
- Access Control Lists (ACL)
- Inter-VLAN Routing

## Network Segmentation

The network is divided into multiple VLANs to separate users and improve security.

| VLAN | Name | Purpose |
|---|---|---|
| 10 | ADMIN | Administration users |
| 20 | STAFF | Staff users |
| 30 | GUEST | Guest users |

## Network Security

### Port Security

Port Security was configured on switch access ports to control which devices are allowed to connect to the network.

### SSH

SSH was configured to provide secure remote access to network devices.

### Access Control Lists (ACL)

Access Control Lists were used to control communication between different networks.

The Guest network is restricted from accessing sensitive internal networks such as the Administration and Staff networks.

### DHCP

DHCP was configured to automatically provide IP addresses to clients in the different VLANs.

## Inter-VLAN Communication

Inter-VLAN Routing allows communication between VLANs when permitted by the network security policies.

ACL rules are used to restrict unauthorized communication between network segments.

## Project Objectives

- Design a segmented network infrastructure.
- Configure VLANs for network separation.
- Configure DHCP for automatic IP addressing.
- Configure SSH for secure device management.
- Implement Port Security.
- Configure ACLs to control network traffic.
- Test connectivity between different network segments.
- Apply basic network security principles.

## Project File

The Cisco Packet Tracer project file is included in this repository:

`project.pkt`

The file can be downloaded and opened using Cisco Packet Tracer.

## Testing

Connectivity and configurations were tested using commands such as:

```text
ping
ipconfig
show vlan brief
show ip interface brief

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

Skills Demonstrated

This project demonstrates practical knowledge of:

* Network Configuration
* Network Segmentation
* Cisco IOS
* VLAN Configuration
* DHCP Configuration
* SSH Configuration
* Switch Security
* Access Control Lists
* Inter-VLAN Routing
* Network Troubleshooting

Author

Mohammed

Cybersecurity Student
Focus: Networking & Penetration Testing

show access-lists
show running-config
