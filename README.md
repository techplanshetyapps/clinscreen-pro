# TrialSentry AI: Governed Clinical Trial Patient Screening & Regulatory Audit 

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> 
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" /> 
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" /> 
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /> 
  <img src="https://img.shields.io/badge/Lyzr_AI-FF6F61?style=for-the-badge&logo=openai&logoColor=white" />
</p>

--- 

## Overview This repository contains a comprehensive enterprise-grade application stack powered by a **FastAPI Backend Container**, styled with a **Next.js React Frontend**, and supercharged with **Lyzr Agent API**, **Lyzr Safe AI**, and **AIMS Governance Layer**. The platform is designed to tackle advanced hackathon and open innovation challenges spanning clinical research, biomedical data processing, and regulatory compliance. --- ## Architecture & Dashboard Preview

--- 

## Chosen Datasets for Analysis The following data formats and sources have been selected as primary inputs for ingestion, validation, and testing across our defined problem statements, ensuring adaptability across diverse biomedical data structures. ### Clinical Trial Protocols and Synthetic EHR Records * **Source:** Clinical Trial Protocol PDFs & Synthetic Patient EHR Bundles (JSON/Text/PDF) * **Application:** Serves as the backbone for multi-format ingestion, criteria extraction, and deterministic patient matching workflows. * **Dataset Utility:** It provides the unstructured clinical text and patient telemetry required to evaluate biomarker thresholds, parse inclusion/exclusion rules, and generate FDA-compliant audit trails safely.

 ---
 
## Technology Stack & Architecture 
* **Backend / API:** FastAPI Server (Python 3.10+) 
* **Frontend / UX:** Next.js (React / TypeScript), TailwindCSS, Responsive Layouts 
* **AI & Multi-Agent Orchestration:** Lyzr Agent API (`Environment`, `Agent`, `Inference`) 
* **Data Security & Privacy:** Lyzr Safe AI Module (Automated PII/PHI scrubbing before inference)
* **Compliance & Observability:** Lyzr AIMS Governance Layer (Verifiable clinical execution trails)
* **Vector Database:** FAISS (High-performance vector similarity search over clinical trial protocols and EHRs)
* **Deployment & Containerization:** Vercel (Frontend & Serverless deployment) + Docker & Docker Compose (Full-stack microservices orchestration)

---

## Problem Statement Addressed 
### Problem Statement Set 
Governed Clinical Trial Patient Screening & Regulatory Audit Agent) Focuses on health tech, bio-pharma, and clinical research. It addresses the systemic challenge where clinical trial recruitment causes up to 40% of trial delays because coordinators must manually parse 100+ page protocols against unstructured electronic health records (EHRs) and lab reports. Standard LLMs fail in this domain due to hallucinated biomarker thresholds that risk enrolling ineligible patients, potential PHI leaks into logs, and strict regulatory requirements for immutable, step-by-step eligibility reasoning mandated by FDA 21 CFR Part 11. 
1. **Multi-Format Ingestion Engine:** Ingests unstructured patient EHR/lab data and massive clinical trial protocol PDFs into a secure Lyzr environment. 
2. **Protocol Criteria Agent:** Extracts complex inclusion/exclusion rules (e.g., eGFR thresholds, HbA1c ranges, washout windows) into structured JSON conditions. 
3. **Safe AI PHI Scrubbing:** Utilizes Lyzr Safe AI to automatically redact and normalize protected health information before inference, ensuring zero unmasked identifiers in logs. 
4. **Medical Safety & Deterministic Matching:** Executes biomarker and medical history matching validated against clinical ontologies (SNOMED-CT, ICD-10, LOINC) to deliver verifiable eligibility statuses. 
5. **Regulatory Audit & AIMS Governance:** Generates immutable FDA-style audit dossiers complete with source citations, confidence scores, and live event streams to Lyzr AIMS. 
6. **Clinical Coordinator UX:** Delivers a streamlined interface with highlighted EHR evidence, automated decision paths, and human-in-the-loop (HITL) webhook safeguards.