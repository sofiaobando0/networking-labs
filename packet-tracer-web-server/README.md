# Cisco Packet Tracer — Web Server Connectivity

## Overview

This lab demonstrates basic network connectivity between a client computer and a web server using Cisco Packet Tracer.

## Objectives

- Verify connectivity between a client and a web server using ICMP.
- Observe basic network communication.
- Access a web server using its IPv4 address.
- Understand the relationship between ARP, IP, TCP, and HTTP.

## Lab Environment

- Tool: Cisco Packet Tracer
- Client: PC0
- Web Server: 172.33.100.50
- Protocols: ICMP, ARP, TCP, HTTP

<img width="1893" height="1029" alt="Screenshot 2026-10-06 131126" src="https://github.com/user-attachments/assets/d0ed923a-062c-4694-b9e9-d8c2ab03eb3f" />
<img width="403" height="198" alt="Screenshot 2026-10-06 131112" src="https://github.com/user-attachments/assets/9cdb2da0-f785-4079-9f02-dc211001ecc5" />
<img width="1915" height="1033" alt="Screenshot 2026-10-06 131032" src="https://github.com/user-attachments/assets/fbb322c2-f742-40b2-8745-8ff7c949b6a1" />


## Tasks Completed

### 1. Connectivity Test

A ping test was performed from PC0 to the web server:

`ping 172.33.100.50`

The test verified connectivity between the client and the web server.

### 2. Web Server Access

The web server was accessed from PC0 using the Packet Tracer web browser:

`http://172.33.100.50`

The web page successfully loaded, confirming HTTP connectivity.

## Network Concepts Demonstrated

- IPv4 addressing
- ICMP
- ARP
- TCP
- HTTP
- Client-server communication
- Basic network troubleshooting

## Communication Flow

```text
PC0
 ↓
ARP
 ↓
IPv4
 ↓
TCP
 ↓
HTTP
 ↓
Web Server<img width="1915" height="1033" alt="Screenshot 2026-10-06 131032" src="https://github.com/user-attachments/assets/c158e4a1-e5fd-429b-b066-da3890ce19c5" />
