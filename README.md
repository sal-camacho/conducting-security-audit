# 🔐 Internal Security Audit — Botium Toys
## 🧠 Activity Scenario: Botium Toys Security Audit

This audit was conducted as part of the Google Cybersecurity Certificate program to assess Botium Toys’ internal security posture. Botium Toys is a small U.S. business managing both physical retail and online operations. As the company expands, its IT department faces growing pressure to secure assets, maintain compliance, and support international e-commerce demands.

### 🔍 Scope of the Audit

- Review the entire security program at Botium Toys
- Assess internal processes and asset management
- Evaluate controls and compliance best practices using the NIST Cybersecurity Framework (CSF)

### 🎯 Audit Goals

- Identify and assess all IT-managed assets
- Complete the controls and compliance checklist
- Determine gaps and recommend improvements to strengthen security posture

### 🧱 Current Assets

- On-premises business equipment
- Employee devices (desktops, smartphones, workstations)
- Retail and warehouse inventory systems
- Software/services (accounting, telecom, database, security, ecommerce)
- Internet access and internal network infrastructure
- Data retention and legacy system management

### ⚠️ Risk Assessment

- **Risk Score**: 8/10 (High)
- Botium Toys lacks proper controls and may not meet U.S. and international compliance standards
- Employees currently have access to sensitive data (cardholder info, PII/SPII)
- No encryption in place for stored credit card data
- No formal access controls, backups, or centralized password policy
- No intrusion detection system (IDS)
- Physical security is in place, but system-level protections are limited

The audit follows NIST CSF's **Identify** function to evaluate risks and establish stronger security practices.

## ✅ Controls and Compliance Checklist

| Control                       | Implemented | Explanation |
|------------------------------|-------------|-------------|
| Least Privilege              | ❌ No        | All employees have access to customer data; privileges need limiting to reduce breach risk. |
| Disaster Recovery Plans      | ❌ No        | No plans in place; essential for ensuring business continuity. |
| Password Policies            | ❌ No        | Minimal requirements may allow unauthorized access to data. |
| Separation of Duties         | ❌ No        | Needs implementation to reduce fraud and limit access to critical data. |
| Firewall                     | ✅ Yes       | Firewall blocks traffic based on defined security rules. |
| Intrusion Detection System   | ❌ No        | Needed to detect intrusions by threat actors. |
| Backups                      | ❌ No        | No backups of critical data exist, jeopardizing business continuity. |
| Antivirus Software           | ✅ Yes       | Installed and monitored regularly. |
| Legacy System Monitoring     | ❌ No        | Systems are monitored but lack scheduled maintenance and clear intervention policies. |
| Encryption                   | ❌ No        | Not used; sensitive data confidentiality is at risk. |
| Password Management System   | ❌ No        | Absence reduces productivity and weakens access control. |
| Physical Locks               | ✅ Yes       | Main offices and storefront are physically secured. |
| CCTV Surveillance            | ✅ Yes       | Functional surveillance is in place. |
| Fire Detection/Prevention    | ✅ Yes       | Active fire alarm and sprinkler systems installed. |

## 📋 Compliance Checklist

### Payment Card Industry Data Security Standard (PCI DSS)

| Practice                                           | Compliant | Explanation |
|---------------------------------------------------|-----------|-------------|
| Authorized access to credit card data             | ❌ No      | All employees have unrestricted access. |
| Secure transaction environment                    | ❌ No      | No encryption for internal credit card processing. |
| Data encryption procedures                        | ❌ No      | Financial info is stored unencrypted. |
| Secure password management policies               | ❌ No      | Weak password policies, no management system. |

### General Data Protection Regulation (GDPR)

| Practice                                           | Compliant | Explanation |
|---------------------------------------------------|-----------|-------------|
| E.U. customer data confidentiality                | ❌ No      | Encryption is not used to secure financial data. |
| Breach notification within 72 hours               | ✅ Yes     | A plan is in place to notify E.U. customers. |
| Proper data classification and inventory          | ❌ No      | Assets are inventoried, but not classified. |
| Enforced privacy documentation                    | ✅ Yes     | Privacy policies and procedures are in place. |

### System and Organizations Controls (SOC 1 & 2)

| Practice                                           | Compliant | Explanation |
|---------------------------------------------------|-----------|-------------|
| User access policies                              | ❌ No      | Least Privilege and Separation of Duties are not enforced. |
| Sensitive data confidentiality (PII/SPII)         | ❌ No      | No encryption for sensitive personal data. |
| Data integrity                                     | ✅ Yes     | Consistency and validation are ensured. |
| Authorized access control                         | ❌ No      | Access isn't limited to role-based need. |

## 🧠 Summary

To improve its security posture and reduce regulatory risk, Botium Toys should implement the following high-priority controls and practices:

- Enforce **Least Privilege access policies** and **Separation of Duties** across teams
- Establish a **Disaster Recovery Plan** and perform **regular backups** of critical data
- Implement stronger **Password Policies** and a **Centralized Password Management System**
- Install an **Intrusion Detection System (IDS)** to identify active threats
- Introduce **Encryption protocols** for credit card data, PII/SPII, and other sensitive assets
- Schedule and document **Legacy System Maintenance**, including formal intervention policies
- Fully classify assets based on sensitivity to enable risk-based prioritization

Botium Toys is currently compliant in areas like physical security and breach notification; however, gaps remain in PCI DSS, GDPR, and SOC standards that must be addressed to protect customers and support future growth.

![Audit Scenario Snapshot](botium-audit-scenario.png)


![1](https://github.com/user-attachments/assets/7cabe52b-89e4-4399-87d6-894d4dc05935)
![2](https://github.com/user-attachments/assets/9338d03f-4bd4-4af3-934f-431b7fd2301a)
![3](https://github.com/user-attachments/assets/c25a9e7f-89dd-412d-a034-8b2dbff32f5e)
![4](https://github.com/user-attachments/assets/4b3795ed-711c-4b69-9b19-576e91dde3f8)
![5](https://github.com/user-attachments/assets/23dcf93d-5546-4fe4-9f95-153ec0d5f10b)
![6](https://github.com/user-attachments/assets/94adf5a9-f7c1-49a1-821e-937b1a0354fc)
![7](https://github.com/user-attachments/assets/c5054a0f-c90a-4c7c-89d5-017096661626)
![8](https://github.com/user-attachments/assets/37ea8b60-4450-4497-9c3f-6ef1247b5935)
![9](https://github.com/user-attachments/assets/f8187373-c67e-4e94-a757-b3b1b1fd7b27)
![10](https://github.com/user-attachments/assets/4f1b50bc-9df5-4207-aba7-20bba545bbbc)
![11](https://github.com/user-attachments/assets/f38bfe24-fb0e-4f0d-8ff9-01ff25e511bf)
![12](https://github.com/user-attachments/assets/72cdc12f-6fb9-429a-9020-6b777193b0c0)
