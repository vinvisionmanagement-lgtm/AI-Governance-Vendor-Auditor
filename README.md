Project: AI-Governance-Vendor-Auditor
A prototype for automating HIPAA and ISO 42001 compliance checks in vendor contracts.

Overview
This repository hosts a proof-of-concept for an automated Artificial Intelligence Management System (AIMS) tool. The goal is to quickly assess third-party AI vendors against critical governance, risk, and compliance (GRC) standards, specifically within regulated industries (Legal & Healthcare).

This project was developed using Python and leverages Natural Language Processing (NLP) to identify risk patterns in unstructured text (e.g., vendor privacy policies, terms of service, BAAs).

Problem Solved
Organizations in FinTech and Healthcare are struggling to vet AI vendors fast enough while maintaining compliance with rigorous standards like HIPAA and emerging AI regulations (like the EU AI Act). This tool provides a rapid, structured way to operationalize vendor risk management and mitigate "shadow AI" usage.

Technical Approach
Language: Python (Jupyter Notebooks)
Libraries: spaCy (for NLP and semantic similarity analysis), os

Methodology: The tool uses rule-based logic and word vectors to:
Scan text for keywords indicating high-risk clauses (e.g., Indemnification).
Identify the absence of required terms (e.g., a missing Business Associate Agreement (BAA) mention).
Calculate similarity scores (e.g., identifying concepts similar to "patient privacy") to find nuanced risks.

Development: Leveraging AI-assisted development has allowed for rapid prototyping and iterative testing of the core governance logic.

Regulatory Alignment
This project directly addresses controls within two major frameworks:
ISO/IEC 42001:2023 (AIMS): Addresses Annex A controls related to AI risk assessment, data quality, and third-party engagement.
HIPAA (Health Insurance Portability and Accountability Act): Focuses on the Privacy Rule and Security Rule requirements for handling Protected Health Information (PHI) within AI systems.

Key Skills Demonstrated
AI Governance & Risk Management
Third-Party Vendor Risk Management (Experience from T-Mobile Cybersecurity Ops)
Legal & Compliance Process Implementation (Experience from The Coca-Cola Company Legal Tech)

## Features (2025 Update)
1. Flags specific AIGP-relevant terms.
2. Assigns risk levels (Very High to Low).
3. Exports a structured CSV audit report for legal/compliance teams.
