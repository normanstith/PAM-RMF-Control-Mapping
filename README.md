# CyberArk PAM – RMF & NIST 800-53 Control Mapping

## Overview

This project demonstrates how **CyberArk Privileged Access Management (PAM)**
capabilities support **Risk Management Framework (RMF)** requirements and
**NIST SP 800-53 security controls** in federal environments.

The focus is on translating **technical PAM controls into audit-ready evidence**
used during Authorization to Operate (ATO) and continuous monitoring.

---

## Mission & Security Objective

**Objective:**  
Provide clear, defensible mapping between CyberArk PAM capabilities and
federal security controls to support accreditation and audit activities.

**Operational Impact:**
- Reduces ambiguity during audits
- Accelerates ATO reviews
- Improves coordination between engineering and compliance teams

---

## Scope

### In Scope
- CyberArk PAS components (Vault, CPM, PSM, PVWA)
- Privileged access workflows
- Audit artifacts and evidence mapping

### Out of Scope
- Full system security plans (SSPs)
- Non-PAM control families

---

## RMF Control Families Supported

| Control Family | Description |
|---------------|------------|
| AC | Access Control |
| IA | Identification & Authentication |
| AU | Audit & Accountability |
| CM | Configuration Management |
| CP | Contingency Planning |

---

## Example Control Mapping

### AC-6 – Least Privilege
- Privileged access restricted via CyberArk safes
- Time-bound approvals enforced
- No standing privileged access

### IA-5 – Authenticator Management
- Automated credential rotation via CPM
- No hard-coded or shared credentials

### AU-12 – Audit Generation
- Full session recording via PSM
- Vault and access logs retained for review

---

## Audit Evidence Produced

- Session recordings
- Credential rotation logs
- Safe membership exports
- Configuration baselines

---

## Federal Relevance

This repository reflects how PAM engineers support:
- ISSOs
- Security Control Assessors (SCAs)
- Continuous Monitoring teams

---

## Disclaimer

This repository is for demonstration purposes only.
