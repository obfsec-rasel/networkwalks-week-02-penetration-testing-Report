<div align="center">

# Networkwalks Week 02 Penetration Testing Project

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  
</p>

---

## Footprinting and Network Scanning Phases

This repository contains my Week 2 practical cybersecurity project, completed as part of the Networkwalks Cybersecurity and Ethical Hacking Internship Program, Batch B082.

The project covers two authorized security-assessment activities:

1. Footprinting and reconnaissance using Kali Linux.
2. Network scanning and discovery using Zenmap/Nmap.

All activities were performed only against systems and networks for which permission had been obtained or that I personally owned.

## Project Information

| Field | Details |
|---|---|
| Author | Sheikh Rasel Mehedi |
| Program | Networkwalks Cybersecurity and Ethical Hacking |
| Batch | B082 |
| Week | 02 |
| Report | W2-PM-FINAL |
| Date | 24 August 2026 |
| Organization | Networkwalks |
| Assessment scope | Authorized domain and personal local network |

## Modules Completed

- **W2-PM1:** Multiple Kali Linux Tools
- **W2-PM5:** Zenmap Scanning

## Activities Covered

### 1. Footprinting and Reconnaissance

The following Kali Linux tools were used to collect publicly available information about the authorized target domain:

- **WHOIS:** Domain-registration and name-server information
- **WhatWeb:** Web-technology fingerprinting
- **NSLOOKUP:** Domain and DNS resolution
- **cURL:** HTTP response-header analysis
- **Wafw00f:** Web Application Firewall detection
- **DNSRecon:** DNS-record enumeration

The reconnaissance phase focused on identifying domain information, DNS records, web technologies, HTTP headers, WAF indicators, and other publicly available details.

### 2. Network Scanning with Zenmap

Zenmap/Nmap was used to perform discovery on my personally owned local network. The activity included:

- Identifying the local IP address and LAN subnet
- Discovering live hosts
- Recording IP addresses
- Identifying MAC addresses where available
- Visualizing network relationships
- Generating a network-topology map

## Tools and Technologies

- Kali Linux
- Windows
- WHOIS
- WhatWeb
- NSLOOKUP
- cURL
- Wafw00f
- DNSRecon
- Nmap
- Zenmap
- Windows Command Prompt

## Key Learning Outcomes

This project helped me develop practical knowledge of:

- Passive and active reconnaissance
- Domain and DNS information gathering
- Web-technology identification
- HTTP response-header analysis
- WAF detection
- DNS enumeration
- Host discovery
- IP and MAC-address identification
- Network-topology visualization
- Security evidence collection
- Technical report writing

The project also demonstrated how footprinting and network scanning complement each other. Footprinting provides external information about a target, while network scanning helps identify reachable systems and understand network structure within an authorized environment.

## Risk Observations

The assessment identified several observations that may require further review:

- Web-technology and version information was publicly identifiable.
- The domain resolved to a publicly visible IP address.
- HTTP response headers provided technical information.
- A possible ModSecurity WAF was identified.
- DNS records revealed information about domain infrastructure.
- Multiple live hosts were visible on the authorized local network.

These observations do not confirm exploitable vulnerabilities. No exploitation or vulnerability validation was performed during these modules.

## Recommendations

- Review publicly exposed technology information.
- Keep CMS platforms, plugins, and other software updated.
- Review HTTP response headers for unnecessary technical details.
- Periodically review publicly available DNS records.
- Keep the WAF enabled, properly configured, and monitored.
- Perform regular authorized network discovery.
- Investigate unknown or unexpected devices.
- Maintain accurate network documentation.
- Conduct all security testing within an approved scope.

## Evidence

The repository may include the following supporting materials:

- Tool-output screenshots
- DNS and domain-reconnaissance results
- HTTP-header output
- WAF-detection results
- Windows network-configuration output
- Zenmap host-discovery results
- IP and MAC-address information
- Network-topology map
- Final penetration-testing report

## Authorization and Disclaimer

All activities documented in this repository were performed for educational purposes within an authorized environment. Testing was limited to the approved target domain and my personally owned local network.

Do not use these techniques against systems or networks without explicit permission. Unauthorized access, scanning, or enumeration may violate applicable laws and organizational policies. The author, instructor, and Networkwalks are not responsible for misuse of the information contained in this repository.

## Project Status

- Footprinting and reconnaissance: Completed
- Network scanning and discovery: Completed
- Documentation and reporting: Completed
- Further assessment phases: In progress

👤 Author

**Sheikh Rasel Mehedi**\
Cybersecurity Professional B082

LinkedIn: [https://www.linkedin.com/in/obfsec-rasel/](https://www.linkedin.com/in/obfsec-rasel/)


Instructor/ Mentor: Waqas Karim

Instructor LinkedIn Profile: https://linkedin.com/in/waqaskarim/

Internship Firm: Network Walks

Internship Duration: 1 Month
---


📌 Project Information
Program Name: Cybersecurity program at Networkwalks | Week: 02 | Repository: GitHub
