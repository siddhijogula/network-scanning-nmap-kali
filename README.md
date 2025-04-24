# Network Scanning and Enumeration with Nmap on Kali Linux

## 📌 Project Overview
This project demonstrates how to use **Nmap** to scan and enumerate devices on a local network using **Kali Linux**. It covers basic scanning, port detection, service versioning, OS detection, and aggressive scanning techniques.

## 🛠️ Tools Used
- **Kali Linux**
- **Nmap** (Network Mapper)

## 📂 Tasks Covered
1. Basic Network Scan
2. Scanning for Specific Ports
3. Service Version Detection
4. Operating System Detection
5. Aggressive Scanning

## 🧪 Sample Commands
```bash
nmap 192.168.1.0/24                # Basic scan
nmap -p 80 192.168.1.0/24          # Scan for port 80
nmap -sV 192.168.1.0/24            # Detect service versions
sudo nmap -O 192.168.1.0/24        # OS detection
sudo nmap -A 192.168.1.0/24        # Aggressive scan
