# Network Security Analyzer  

A Python-based tool to monitor and analyze live network traffic for potential security threats. This project demonstrates network packet sniffing, analysis, and basic vulnerability detection.  

## Features  
- Real-time network packet capture using Scapy  
- Detection of suspicious activities such as:
  - **Port Scans**: Identifies multiple connection attempts to different ports in a short time.
  - **ARP Spoofing**: Detects MAC address spoofing on your local network.
- Summarizes suspicious activity detected during monitoring.

## Prerequisites  
To run this script, you need the following:  
1. **Python 3.x**: [Download Python](https://www.python.org/).  
2. **Npcap**: [Download and Install Npcap](https://nmap.org/npcap/).  
   - Ensure to check the box for **"Install Npcap in WinPcap API-compatible Mode"** during installation.  

## Installation  
1. **Clone this Repository**:  
   Open your terminal and run:
   ```bash
   git clone https://github.com/yourusername/network-security-analyzer.git
   cd network-security-analyzer
