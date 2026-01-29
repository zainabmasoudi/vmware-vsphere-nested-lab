# VMware vSphere Nested Lab (ESXi + vCenter)

## Overview
This project demonstrates the deployment of a nested VMware vSphere environment using VMware Workstation. 
The lab simulates a real enterprise setup with multiple ESXi hosts managed by vCenter Server.

## Architecture
- VMware Workstation 17 (physical host simulation)
- 3 x ESXi 7.x hosts (nested)
- 1 x vCenter Server Appliance (VCSA)
- Active Directory integration
- VLAN-based virtual networking
- vMotion-enabled cluster

## Key Features
- ESXi installation, patching, and configuration
- vCenter Server Appliance deployment
- Cluster creation and management
- vMotion configuration and testing
- Active Directory authentication
- Datastore and ISO management
- Troubleshooting OVA/OVF deployment issues

## Technologies Used
- VMware Workstation 17
- VMware ESXi 7.x
- VMware vCenter Server
- Active Directory
- Ubuntu Server
- VLANs & vSwitches

## Outcome
Successfully migrated a running VM between ESXi hosts using vMotion with zero downtime.

## Disclaimer
This lab is for educational purposes only. No production data is used.
