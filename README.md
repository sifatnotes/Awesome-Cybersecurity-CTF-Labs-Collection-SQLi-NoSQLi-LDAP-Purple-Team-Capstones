# Database Injection & Security Specialist Capstone CTF Labs Collection

A structured, searchable index of hands-on cybersecurity labs focusing on advanced database injection techniques (Blind SQLi, Time-Based SQLi, Boolean Blind SQLi, Second-Order SQLi, Out-of-Band DNS Exfiltration, NoSQL Injection, LDAP Injection) alongside role-based cybersecurity capstone challenges (Cloud Security Architect, Purple Team Specialist, Incident Response, Blue Team Operator) hosted on Learn SecByte.

This collection is designed for penetration testers, security analysts, database administrators, red/blue/purple team practitioners, and cybersecurity students seeking comprehensive offensive and defensive domain training.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
  - [SQL Injection & Blind Data Exfiltration](#sql-injection--blind-data-exfiltration)
  - [NoSQL & Directory (LDAP) Injections](#nosql--directory-ldap-injections)
  - [Specialist Capstones & Role-Based Security](#specialist-capstones--role-based-security)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Securing enterprise applications requires mastering both specialized injection mechanics and broad architectural security. Database injections—ranging from complex blind SQL exfiltration over DNS to NoSQL query operator abuse—remain critical threat vectors. Integrating these offensive findings with blue team detection, cloud architecture, and purple team incident response forms the ultimate test of cybersecurity readiness.

This repository organizes hands-on cybersecurity labs from Learn SecByte into logical learning paths covering advanced database auditing and end-to-end incident analysis.

---

## Lab Collection & Index

| Lab Title | Target Focus | Primary Category | Access Link |
| :--- | :--- | :--- | :--- |
| **LDAP Injection** | Directory Services | Authentication & Filter Bypass | [Access Lab](https://learn.secbyte.org/ctf/ldap-injection-from-basics-to-bypass) |
| **NoSQL Injection** | Document Databases | Query Operator Abuse | [Access Lab](https://learn.secbyte.org/ctf/nosql-injection-from-query-logic-to-defense) |
| **Second-Order SQL Injection** | SQL Databases | Stored Input Exploitation | [Access Lab](https://learn.secbyte.org/ctf/second-order-sql-injection) |
| **Out-of-Band SQL Injection** | SQL Databases | DNS & Out-of-Band Exfiltration | [Access Lab](https://learn.secbyte.org/ctf/out-of-band-sql-injection-blind-paths-dns-exfiltration-and-d) |
| **Time-Based SQL Injection** | SQL Databases | Blind Delay Inference | [Access Lab](https://learn.secbyte.org/ctf/time-based-sql-injection-blind-to-the-clock) |
| **Boolean-Based Blind SQLi** | SQL Databases | True/False Response Extraction | [Access Lab](https://learn.secbyte.org/ctf/boolean-blind-sql-injection-foundations-to-exploitation) |
| **Blind SQL Injection** | SQL Databases | Probing to Proof | [Access Lab](https://learn.secbyte.org/ctf/blind-sql-injection-from-probe-to-proof) |
| **Cybersecurity Capstone** | Full-Spectrum | End-to-End Incident & Exploitation | [Access Lab](https://learn.secbyte.org/ctf/cybersecurity-capstone-end-to-end-incident-and-exploitation-) |
| **Cloud Architect Security** | Cloud Architecture | Cloud Infrastructure Hardening | [Access Lab](https://learn.secbyte.org/ctf/cloud-architect-security-foundations) |
| **Security Consultant Advisory** | Incident Response | Advisory to Incident Mitigation | [Access Lab](https://learn.secbyte.org/ctf/security-consultant-advisory-to-incident-response) |
| **Purple Team Specialist** | Red/Blue Collaboration | Joint Attack & Defense Operations | [Access Lab](https://learn.secbyte.org/ctf/purple-team-specialist) |
| **Blue Team Operator** | Defense / Monitoring | Fundamentals & Detection | [Access Lab](https://learn.secbyte.org/ctf/blue-team-operator-fundamentals-2) |

---

## Categories

### SQL Injection & Blind Data Exfiltration
Hands-on CTF labs detailing relational database exploitation, blind data inference, timing delays, stored second-order execution, and out-of-band exfiltration:

* **Blind SQL Injection:** Probing application responses to prove and extract data without direct error reflection.
  * Lab Link: https://learn.secbyte.org/ctf/blind-sql-injection-from-probe-to-proof
* **Boolean-Based Blind SQLi:** Extracting database contents bit-by-bit by evaluating True/False application states.
  * Lab Link: https://learn.secbyte.org/ctf/boolean-blind-sql-injection-foundations-to-exploitation
* **Time-Based Blind SQLi:** Inferring schema structure and values by injecting database sleep commands (`WAITFOR DELAY`, `pg_sleep()`).
  * Lab Link: https://learn.secbyte.org/ctf/time-based-sql-injection-blind-to-the-clock
* **Out-of-Band SQL Injection:** Using database extensions (e.g., `xp_dirtree`, `UTL_INADDR`) to exfiltrate query results via DNS/HTTP requests to external listeners.
  * Lab Link: https://learn.secbyte.org/ctf/out-of-band-sql-injection-blind-paths-dns-exfiltration-and-d
* **Second-Order SQL Injection:** Storing malicious SQL payloads in a database that execute safely initially but trigger during subsequent application queries.
  * Lab Link: https://learn.secbyte.org/ctf/second-order-sql-injection

### NoSQL & Directory (LDAP) Injections
Practical security labs covering non-relational query manipulation and Active Directory/LDAP query filter subversion:

* **NoSQL Injection:** Abusing MongoDB/CouchDB query operators (`$ne`, `$gt`, `$regex`) to bypass authentication and dump documents.
  * Lab Link: https://learn.secbyte.org/ctf/nosql-injection-from-query-logic-to-defense
* **LDAP Injection:** Manipulating Lightweight Directory Access Protocol (LDAP) filter syntax (`&`, `|`, `!`) to bypass login forms and enumerate directory objects.
  * Lab Link: https://learn.secbyte.org/ctf/ldap-injection-from-basics-to-bypass

### Specialist Capstones & Role-Based Security
Comprehensive scenario-driven capstone labs combining attack techniques with threat hunting, blue teaming, cloud architecture, and strategic advisory:

* **Cybersecurity Capstone:** Full-spectrum end-to-end incident investigation, initial exploitation, post-exploitation, and remediation reporting.
  * Lab Link: https://learn.secbyte.org/ctf/cybersecurity-capstone-end-to-end-incident-and-exploitation-
* **Cloud Architect Security Foundations:** Hardening cloud perimeters, auditing IAM infrastructure, and enforcing secure architectural design patterns.
  * Lab Link: https://learn.secbyte.org/ctf/cloud-architect-security-foundations
* **Security Consultant Advisory:** Bridging technical exploitation with strategic incident response, executive advisory, and remediation management.
  * Lab Link: https://learn.secbyte.org/ctf/security-consultant-advisory-to-incident-response
* **Purple Team Specialist:** Executing collaborative adversary emulation to evaluate SIEM rules, SOC detection coverage, and defensive posture.
  * Lab Link: https://learn.secbyte.org/ctf/purple-team-specialist
* **Blue Team Operator Fundamentals:** Operational security defense, log analysis, threat hunting, and incident detection methodologies.
  * Lab Link: https://learn.secbyte.org/ctf/blue-team-operator-fundamentals-2

---

## Learning Path

Follow this structured roadmap to master database security auditing and progress to enterprise capstone challenges:

1. **Non-Relational & Directory Injections**
   - Practice LDAP injection filter manipulation and NoSQL query operator abuse.
2. **Advanced SQL Injection & Blind Exfiltration**
   - Progress from Boolean-based True/False testing to Time-based execution delays.
   - Execute Out-of-Band (OOB) DNS exfiltration and analyze Second-Order SQLi stored execution paths.
3. **Defensive Operations & Threat Hunting**
   - Master Blue Team operator fundamentals and monitor SIEM telemetry for injection indicators.
4. **Purple Teaming & Specialist Capstones**
   - Participate in Purple Team operations to validate security controls.
   - Complete full-spectrum capstone scenarios covering cloud security architecture and incident advisory.

---

## How to Use the Labs

1. Select a scenario from the index table or category sections above.
2. Launch the interactive target environment directly on Learn SecByte.
3. Utilize tools such as Burp Suite, sqlmap, custom Python scripts, or OOB listeners (e.g., interactsh) to execute queries, trigger time delays, capture DNS callbacks, and perform log analysis.
4. Review defensive baselines to learn how parameterized queries (Prepared Statements), ORM parameter binding, input validation, and SIEM detection rules mitigate these risks.

---

## Disclaimer

This repository is strictly intended for educational research, authorized security testing, and defensive engineering training. All concepts, techniques, and lab environments are provided to help cybersecurity practitioners identify vulnerabilities and harden enterprise systems. Unsanctioned testing or attacks against external infrastructure without prior written authorization are strictly illegal.# Awesome-Cybersecurity-CTF-Labs-Collection-SQLi-NoSQLi-LDAP-Purple-Team-Capstones
A curated index of hands-on CTF labs covering Blind SQL Injection, Out-of-Band SQLi, NoSQLi, LDAP Injection, and Capstone challenges for Blue, Purple, and Cloud Security roles from Learn SecByte.
