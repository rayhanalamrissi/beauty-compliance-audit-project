# 💄 Third-Party Compliance Audit - Beauty Industry

## 📌 Project Overview
As a Data Privacy & Compliance Analyst, I developed this tool to automate the risk assessment of 500+ global vendors (Raw material suppliers, Influencer agencies, R&D labs). 

The goal is to protect the company from **GDPR fines** and **financial fraud** by identifying non-compliant partners in real-time.

## 📊 Compliance Dashboard
![Compliance Dashboard](compliance_dashboard.png)

## 🛠️ Audit Methodology (Data Logic)
I implemented automated verification rules using Google Sheets/Excel logic:

1. **Privacy Risk Check**: Flags any partner accessing personal data without a signed **DPA** (Data Processing Agreement).
2. **Financial Integrity Check**: Detects mismatches between **HQ Country** and **Bank Country** (Anti-fraud/Shell company detection).
3. **Global Status**: Categorizes partners as **'CRITICAL'** for immediate remediation or **'COMPLIANT'**.

## 🚀 Business Value
- **Scalability**: Capable of auditing thousands of rows instantly.
- **Risk Mitigation**: Visualizes high-risk areas to prioritize Legal Department interventions.
- **Data Governance**: Ensures Article 28 GDPR compliance across the supply chain.

## 📁 Files in this Repository
- `Compliance_Audit_Tool.xlsx`: The complete audit file with formulas and data.
- `compliance_dashboard.png`: Visual summary of risk distribution.
