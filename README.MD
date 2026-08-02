# Hi, I'm Pranav Dagay 👋

**Detection Engineer | SIEM Content Engineering | MITRE ATT&CK-Mapped Detections**

📍 Pune, India | 📧 pranavdagay@gmail.com | [LinkedIn](https://linkedin.com/in/pranav-dagay-0b0577286/)

---

## About Me

I build detection logic that catches real threats — not proof-of-concepts, production content running in live customer environments. I own the full detection engineering pipeline: taking raw logs from a provider, understanding their structure, building normalization layers, and writing MITRE ATT&CK-mapped detections for anomalies, UBA, and DLP on top of them.

I've done this across 10+ enterprise log sources — Linux, Windows, Palo Alto, CrowdStrike, Netskope, Zscaler, CyberArk, FortiGate, Kaspersky, Proofpoint, and more — each with different log formats, different attacker behaviors, and different failure modes to design around.

I care about detections that survive contact with real data — low false-positive rates, clear escalation logic, and documented reasoning an incident responder can trust at 3am.

---

## 🔍 Featured Projects

| Project | Description | Tools |
|---|---|---|
| ATT&CK Detection Portfolio *(coming soon)* | Sanitized, from-scratch detection rules mapped to specific MITRE ATT&CK techniques, with documented false-positive analysis | Sigma, Python |
| SIEM Content Engineering Agent *(in progress)* | AI-driven pipeline that automates parser, dictionary, and detection generation for new SIEM log providers | Python, LLM agents |
| [BOTS v3 Web Recon Investigation](https://github.com/pranav-dagay/bots-v3-web-recon-investigation) | External web reconnaissance and username enumeration attack against a vBulletin forum server | Splunk, SPL |
| [BOTS v3 False Positive Triage](https://github.com/pranav-dagay/bots-v3-false-positive-triage) | Cross-sourcetype analysis of anomalous internal host behaviour — closed as false positive | Splunk, SPL |
| [BOTS v3 SSH Brute Force Investigation](https://github.com/pranav-dagay/botsv3-ssh-bruteforce-investigation) | DNS anomaly led to confirmed SSH brute force, server compromise, and post-compromise surveillance detection | Splunk, SPL |
| [BOTS v3 Empire C2 Investigation](https://github.com/pranav-dagay/bots-v3-empire-c2-investigation) | Windows Event Log analysis uncovering PowerShell Empire C2 malware on a compromised endpoint | Splunk, SPL |

---
## 🛠️ Core Strengths

- **Detection Engineering** — MITRE ATT&CK-mapped detection logic for anomalies, UBA, and DLP; tuned for production false-positive rates
- **Log Normalization** — Parser & dictionary engineering across 10+ enterprise providers; built to handle malformed, incomplete, and adversarial input
- **Pipeline Ownership** — Raw log ingestion → normalization → detection, end to end, not just one layer
- **SIEM Platforms** — Microsoft Sentinel (KQL), IBM QRadar, Splunk (SPL)
- **Engineering** — Python, Kafka, Redis


## 📜 Certifications

- C3SA ✅
- Google Cybersecurity (Coursera) ✅
- IBM Cybersecurity Badge ✅
- CompTIA Security+ *(in progress)*

---

## 📊 Engineering Philosophy

> I build detections the way I'd want them explained to an incident responder six months from now — clear logic, mapped to a technique, with false-positive conditions documented up front.
