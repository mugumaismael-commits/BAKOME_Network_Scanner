# BAKOME_Network_Scanner
BAKOME Network Scanner – Educational security tool to scan your own network, detect open ports, vulnerable services, and generate PDF reports. Legal use only: verify your own devices to find security holes. No illegal use permitted. Ethical cybersecurity education.
# BAKOME Network Vulnerability Scanner

<p align="center">
  <img src="https://img.shields.io/badge/Security-Scanner-red?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PDF-Report-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Linux-Termux-blue?style=for-the-badge"/>
</p>

## 🛡️ Automated Security Audit Tool

**BAKOME Network Scanner** is a professional-grade security tool that:
- 🔍 Scans your local network for active devices
- 🚪 Detects open ports and vulnerable services
- 📊 Generates detailed PDF reports with recommendations
- 🎯 Helps administrators secure their infrastructure

## ⚠️ Legal Notice
**Use only on networks you own or have permission to test.** Unauthorized scanning may violate laws.

## ✨ Features
- ARP discovery (fast device detection)
- Port scanning (nmap + socket fallback)
- Vulnerability detection (FTP, Telnet, SMB, RDP, MySQL, etc.)
- Professional PDF report with graphs
- Zero external API dependencies

## 🚀 Quick Start

```bash
git clone https://github.com/YOUR_USERNAME/BAKOME_Network_Scanner.git
cd BAKOME_Network_Scanner
pip install -r requirements.txt
sudo python3 network_scanner.py
