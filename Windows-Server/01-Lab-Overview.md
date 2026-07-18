# Windows Server Home Lab Overview

## Project Objective

Build a virtual Windows domain environment to practice Windows Server administration, Active Directory, DNS, DHCP, domain joins, user management, and Group Policy.

## Virtualization Platform

- Hypervisor: Oracle VirtualBox
- Host computer operating system: Windows
- Host CPU: 13th Gen Intel Core i5-13500
- Host CPU cores: 14
- Host logical processors: 20
- Host RAM: 32 GB DDR4

## Installation Media

- Windows Server evaluation ISO: SERVER_EVAL_x64FRE_en-us
- Windows client ISO: Windows 11 25H2 English x64

## Planned Virtual Machines

### Domain Controller

- Operating system: Windows Server Evaluation
- VM name: DC01
- Hostname: DC01
- Role: Domain controller, DNS server, and DHCP server
- Virtual CPUs: 2
- RAM: 4 GB
- Disk size: 60 GB
- Planned IP address: 10.0.0.10

### Client Computer 1

- Operating system: Windows 11 25H2
- VM name: CLIENT01
- Hostname: CLIENT01
- Role: Domain-joined workstation
- Virtual CPUs: 2
- RAM: 4 GB
- Disk size: 64 GB
- IP configuration: DHCP

### Client Computer 2

- Operating system: Windows 11 25H2
- VM name: CLIENT02
- Hostname: CLIENT02
- Role: Domain-joined workstation
- Virtual CPUs: 2
- RAM: 4 GB
- Disk size: 64 GB
- IP configuration: DHCP

## Planned Domain

- Domain name: ad.example.com
- NetBIOS name: EXAMPLE

## Project Status

- [ ] Design virtual network
- [ ] Install Windows Server
- [ ] Configure server networking
- [ ] Install Active Directory
- [ ] Configure DNS
- [ ] Configure DHCP
- [ ] Install Windows client
- [ ] Join client to domain
- [ ] Create users and groups
- [ ] Configure Group Policy
- [ ] Complete testing