# Network-Mapping-Ping-Test-Task
This project provides a structured approach to mapping network topology and performing ping tests to verify connectivity, latency, and reliability across devices. It is designed for IT professionals, system administrators, and network engineers who need clear visibility into their infrastructure.
# 🖧 Network Mapping & Ping Test

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Windows%20%7C%20MacOS-lightgrey)
![Tools](https://img.shields.io/badge/tools-Nmap%20%7C%20Wireshark%20%7C%20Ping-orange)

---

## 📌 Overview
This repository documents the process of **network mapping** and **ping testing** to ensure connectivity, performance, and reliability across devices. It provides scripts, diagrams, and reports for IT professionals and network engineers.

---

## 🎯 Objectives
- Map and visualize the network topology.  
- Identify devices, IP addresses, and roles.  
- Perform ping tests to measure latency and packet loss.  
- Generate reports for troubleshooting and optimization.  

---

## ⚙️ Features
- **Network Mapping**: Automated discovery of nodes and connections.  
- **Ping Testing**: Reachability checks, latency measurement, and packet loss detection.  
- **Topology Diagram**: Visual representation of the network.  
- **Reporting**: Summarized results for audits and scaling.  

---

## 🛠️ Tools & Technologies
- **Mapping**: Nmap, Wireshark, Cisco Packet Tracer, SolarWinds.  
- **Ping Tests**: Native `ping`, `tracert`/`traceroute`, PingPlotter.  
- **Documentation**: Markdown, diagrams, structured reports.  

---

## 🚀 Usage
### Run Ping Test
```bash
ping <IP_ADDRESS>
tracert <IP_ADDRESS>   # Windows
traceroute <IP_ADDRESS> # Linux/MacOS
nmap -sP <NETWORK_RANGE>

