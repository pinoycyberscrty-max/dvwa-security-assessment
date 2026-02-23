DVWA Security Assessment (Safe Recon Project)
This repository contains a safe, non‑intrusive security assessment performed against a DVWA instance running inside an isolated Docker lab. The goal of this project is to demonstrate professional reconnaissance techniques used by SOC analysts and junior penetration testers, focusing only on surface‑level, read‑only analysis.
---
🔍 Project Overview
This assessment covers:
• HTTP Header Analysis
• HTTP Crawler / Directory Mapping
• Authentication Flow Behavior
• Server Response Observation
All testing was performed inside a private Docker network with no external exposure.
No exploitation or intrusive scanning was performed.
---
📁 Repository Structure

dvwa-security-assessment/
│
├── README.md
│
├── scans/
│   ├── headers.txt
│   ├── crawler.txt
│
└── report/
    └── dvwa-security-assessment.md

• scans/ contains raw output from Metasploit modules
• report/ contains the full written assessment
• README.md is the project landing page
---
🧠 What This Project Demonstrates
• Ability to perform safe reconnaissance
• Understanding of HTTP behavior and server responses
• Professional documentation and reporting
• Familiarity with Metasploit recon modules
• Clean, organized, portfolio‑ready project structure
This project is designed to showcase real SOC‑style analysis and documentation skills.
---
🛠️ Tools Used
• Metasploit Framework
	◦ auxiliary/scanner/http/http_header
	◦ auxiliary/scanner/http/crawler
• Docker (isolated lab environment)
• Browser-based manual verification
---
📄 Full Report
The complete assessment is available here:
👉 report/dvwa-security-assessment.md
---
🚀 About This Project
This is part of an ongoing series of hands‑on security lab projects designed to build a strong portfolio for SOC analyst and penetration testing roles.
More assessments and targets will be added over time.
---
