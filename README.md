# University Network Configuration

## Overview
This repository contains the network configuration for a large university with two campuses: Main Campus and Branch Campus. The university has four faculties: Health and Sciences, Business, Engineering/Computing, and Art/Design. Each campus and faculty has specific requirements for network configuration.

## Main Campus

### Building A
- Houses administrative staff (management, HR, finance) and Faculty of Business.
- Implements VLANs for admin PCs to efficiently share networking equipment.

### Building B
- Accommodates Faculty of Engineering and Computing and Faculty of Art and Design.

### Building C
- Contains student labs and the IT department.
- IT department hosts the University Web server and internal servers.
- Email server hosted externally in the cloud.

## Branch Campus
- Faculty of Health and Sciences (staff and students' labs are situated on separate floors).

## Network Configuration

### 1. Department/Faculty-specific IP Networks
- Each department and faculty assigned a separate IP network for efficient management and traffic segmentation.

### 2. VLANs and Security Settings
- VLANs configured on switches for logical network segmentation.
- Security settings implemented to control access and protect sensitive data.

### 3. Dynamic IP Addresses
- Devices of every building or department acquire dynamic IP addresses from a router-based DHCP server for flexibility and efficient IP management.

### 4. Routing Protocols
- RIPv2 used for internal routing among routers within the campus network.
- Static routing configured for external servers to ensure stable and secure communication.

## How to Use
- Clone this repository to your local machine.
- Refer to individual configuration files for specific settings in each building or department.
- Follow the documentation for setting up VLANs, IP networks, and routing protocols.

## Contributors
- [Shivang]
- [Anamika]
- [Amit]
- [Shilpi]
- [Gaurav]

## Network design
<img width="1436" alt="image" src="https://github.com/shivang0203/University-Campus-Network-Design/assets/94477758/648015a8-bc8f-46c9-8f70-4a67e07bd4a8">
