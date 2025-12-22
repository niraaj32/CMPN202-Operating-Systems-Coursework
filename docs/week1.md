# Week 1 – Virtual Machine Setup and Network Configuration

**Module:** CMPN202 – Operating Systems  
**Student Name:** Niraj Kumar Sah  
**Student ID:** A00023606  


## Objective
The objective of Week 1 was to install and configure two virtual machines (Ubuntu Workstation and Ubuntu Server) using Oracle VirtualBox and to establish network connectivity between them.


## Virtual Machine Setup
Two virtual machines were created using Oracle VirtualBox:
- Ubuntu Workstation (GUI-based)
- Ubuntu Server (CLI-based)

Both operating systems were installed successfully.


## Network Configuration
Both virtual machines were configured with a **Host-only Adapter** to allow internal communication between the workstation and the server.

- Network Adapter: Host-only Adapter  
- IP Address Range: 192.168.56.0/24  
- IP addresses were assigned dynamically via DHCP


## Connectivity Testing
Connectivity between the workstation and the server was tested using the `ping` command:

bash
ping <server-ip>


Successful ping responses confirmed that the two virtual machines were connected correctly.

SSH connectivity to the Ubuntu Server was also verified.


## Evidence (Screenshots)

### VirtualBox Virtual Machines
![VirtualBox VMs](assets/screenshots/week1/w1-01-virtualbox-vms.png.png)

### Workstation IP Address
![Workstation IP](assets/screenshots/week1/w1-02-workstation-ip.png)

### Server IP Address
![Server IP](assets/screenshots/week1/w1-03-server-ip.png)

### Workstation to Server Ping
![Ping Test](assets/screenshots/week1/w1-04-workstation-ping.png)

### SSH Connection to Server
![SSH Connection](assets/screenshots/week1/w1-05-workstation-ssh.png)


## Conclusion
Both the Ubuntu Workstation and Ubuntu Server were successfully installed, configured, and connected using a Host-only network adapter. Network communication between the two systems was verified successfully.

