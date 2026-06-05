# Global-Branch-Network-Infrastructure-Simulation

A Cisco Packet Tracer simulation of a multi-site enterprise network connecting the Semarang Office (Indonesia) and Tokyo Office (Japan).

## Overview

This project simulates communication between two branch offices connected through a WAN link. The network provides essential enterprise services including:

- Dynamic Routing
- DNS Service
- DHCP Service
- Web Service
- Inter-office Communication

## Network Topology

### Semarang Office
Network Segments:
- 192.168.3.0/24 (Client Network)
- 192.168.4.0/24 (Server Network)

Services:
- S-Web (Web Server)
- S-DNS (DNS Server)

### Tokyo Office
Network Segments:
- 192.168.0.0/24 (Client Network)
- 192.168.1.0/24 (Server Network)

Services:
- T-Web (Web Server)
- T-DNS (DNS Server)
- T-DHCP (DHCP Server)

## Features

### Dynamic Routing
Routers exchange routing information automatically, allowing communication between all networks.

### DNS Resolution
Users can access web servers using domain names:

- semarang.database.local
- tokyo.database.local

### DHCP
The Tokyo Office clients obtain:
- IP Address
- Default Gateway
- DNS Server

automatically from the DHCP server.

### Web Services
Both offices host their own web servers accessible from remote networks.

## Connectivity Tests

Successful communication was verified between:

- Semarang Client → Semarang Web Server
- Semarang Client → Tokyo Client
- Semarang Client → Tokyo Web Server
- Tokyo Client → Tokyo DNS Server
- Tokyo Client → Semarang Client
- Tokyo Client → Semarang DNS Server

## Tools

- Cisco Packet Tracer

## Author

Raihan Lazuardi
Universitas Diponegoro
