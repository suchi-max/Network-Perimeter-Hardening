# Network Perimeter Hardening & Behavioral Threat Hunting

## Overview

In this project, I built a small virtual network lab and worked on improving its security. I analyzed normal network traffic, performed reconnaissance activities, reduced the attack surface of the web server, and configured firewall rules based on the principle of least privilege. I also investigated different activities through logs and packet captures to understand how normal and suspicious behavior look in a network.

## Lab Setup

| Machine    | IP Address | Role       |
| ---------- | ---------- | ---------- |
| pfSense    | 10.0.0.1   | Firewall   |
| Wazuh      | 10.0.0.10  | SIEM       |
| Ubuntu 16  | 10.0.0.20  | Web Server |
| Windows 7  | 10.0.0.30  | Client     |
| Kali Linux | 10.0.0.40  | Attacker   |

## Tools Used

* Wireshark
* Nmap
* pfSense
* Wazuh
* Apache2
* SSH

## What I Did

* Captured and analyzed ICMP, SSH, and HTTP traffic to understand normal network behavior.
* Performed host discovery, service enumeration, and full port scans using Nmap.
* Reduced the attack surface by disabling unnecessary services on the Ubuntu web server.
* Configured least-privilege firewall rules in pfSense to allow only required traffic.
* Investigated Nmap scans and ICMP flood activity through Wireshark, pfSense logs, and Wazuh alerts.

## Project Files

* `Network Perimeter Hardening & Behavioral Threat Hunting-SuchismitaMaji-05-07-2026PDF.pdf` – Complete project documentation
* `SCREENSHOTProofs/` – Screenshots and evidence collected during the lab
