# OpenSOC Lab — Wazuh SIEM Home Lab
## Overview
OpenSOC Lab is a hands-on Security Operations Center
(SOC) environment built to practice endpoint monitoring,
centralized log collection, and security event analysis.
The environment uses Wazuh on Ubuntu WSL2 and a
Windows 11 endpoint.
## Architecture
- SIEM: Wazuh
- Server environment: Ubuntu on WSL2
- Components: Wazuh Manager, Indexer, Filebeat, Dashboard
- Endpoint: Windows 11
- Endpoint agent: Wazuh Agent
- Additional telemetry tooling: Microsoft Sysmon
## Completed Work
- Deployed the Wazuh SIEM environment.
- Connected one Windows 11 endpoint.
- Verified endpoint telemetry in the Wazuh dashboard.
- Reviewed collected host events for security monitoring.
## Repository Structure
- architecture/ — Architecture diagrams
- configs/ — Configuration references
- detections/ — Detection engineering work
- docs/ — Deployment documentation
- investigations/ — SOC investigation reports
- mitre/ — MITRE ATT&CK mapping
- scenarios/ — Security testing scenarios
- scripts/ — Lab automation
Some folders are reserved for future work.
## Planned Improvements
- Develop and test custom Wazuh detection rules.
- Document repeatable investigation scenarios.
- Map validated detections to MITRE ATT&CK.
- Add sanitized screenshots and investigation evidence.
## Configuration Attribution
The Sysmon configuration used in this lab is based on
Olaf Hartong's Sysmon Modular project:
https://github.com/olafhartong/sysmon-modular
This configuration is third-party material and is not
presented as an original detection ruleset.
## Status
OpenSOC v0.1 — Initial SIEM deployment completed.
## Author
Shamin Naushad
Computer Science (Cybersecurity)
Arizona State University
