# Deep Scope IR

**Incident Response & Forensic Practitioner**  
*Focused on Linux Telemetry, Living off the Land (LotL) Detection, and Stealth Intrusion Analysis.*

---

## 🧠 Research & DFIR Framework

My objective is to move beyond high-level security concepts by dissecting threats down to their fundamental telemetry and OS interactions.

* **Anchor Event & Session Window Isolation:** Reconstructing attack timelines by isolating initial access vectors and correlating session activity within logs and memory.
* **Telemetry Verification:** Every investigation is grounded in raw forensic data—analyzing process trees, file system anomalies, volatile memory artifacts, and authentication records.
* **Living off the Land (LotL) Analysis:** Scrutinizing the misuse of native binaries and administrative tools to identify defense evasion and unauthorized persistence.
* **Evidence-Driven Detection:** Transforming forensic findings into actionable, scalable defense logic through custom Sigma rules and YARA signatures.

---

## 📂 Repository Structure

* `/Investigations`: Technical write-ups and post-mortems of simulated intrusions and ransomware scenarios.
* `/Telemetry-Artifacts`: Log samples, memory extraction notes, and evidence collected during lab triage.
* `/Detections`: Custom Sigma rules, YARA signatures, and detection logic derived from incident research.

---

## 🔬 Current Research & Focus

* **Case Study 04.2:** *Linux Double-Extortion Ransomware: Telemetry Analysis, Persistence Vectors, and Volumetric Crypto Evasion* [IN PROGRESS]
* **Core Topic:** Linux Threat Hunting — Identifying Obfuscated Command Lines & In-Memory Execution
