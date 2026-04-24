# ScanWise AI
### Next-Generation Multimodal Clinical Intelligence Platform
> Unified Diagnostic Reasoning Across Imaging, Laboratories, and EHR Ecosystems.

[![Platform](https://img.shields.io/badge/Platform-Medical--Grade%20AI-blue.svg?style=for-the-badge)]()
[![Engine](https://img.shields.io/badge/Engine-Gemini%203%20Pro-purple.svg?style=for-the-badge)]()
[![Compliance](https://img.shields.io/badge/Compliance-HIPAA%20Aligned-emerald.svg?style=for-the-badge)]()

---

## Academic Context

This project is developed in partial fulfillment of the **University Course Project (CS7032)**.

### Team Members

- Zoya Alam (20211CSE0242)  
- [Faizan Ahmed](https://github.com/FURIOUSCHAMP007) (20221CSE0021)  
- [Siddique Ali Khan](https://github.com/siddiquealikhan) (20221CSE0048)  

---

## Overview

ScanWise AI is an enterprise-grade Clinical Decision Support (CDS) platform designed to eliminate diagnostic silos across radiology, laboratory systems, and electronic health record ecosystems.

By synthesizing:

- High-resolution DICOM imaging  
- Longitudinal laboratory biomarkers  
- Real-time clinical documentation  

the platform establishes a single source of clinical truth for high-confidence triage, differential diagnosis, and transplant intelligence workflows.

Powered by a multi-agent architecture leveraging Gemini 3 Pro and Gemini 3 Flash, ScanWise AI performs deep cross-modal reasoning by verifying imaging abnormalities against biochemical markers and structured EHR tensors.

---

## Core Clinical Modules

### Multimodal Agentic Ingestion

Secure entry layer for all medical data streams.

- AI modality detection (MRI, CT, X-ray, Lab Report)  
- Automated anatomical localization  
- Local PHI/PII stripping prior to cloud inference  
- PACS-ready DICOM compatibility  
- OCR extraction from unstructured documents  

**Output:** Structured, anonymized clinical tensors ready for reasoning.

---

### Clinical Reasoning and Analysis

Cross-modal diagnostic intelligence engine.

- Dual inference pipeline  
  - Gemini 3 Flash for OCR and summarization  
  - Gemini 3 Pro for differential diagnosis modeling  
- Imaging–lab correlation  
- ROI heatmapping for lesion localization  
- Explainable reasoning trees  
- Voice-enabled peer review assistant  

**Output:** High-confidence, transparent diagnostic hypotheses.

---

### Operational Triage Dashboard

Mission-control layer for hospital operations.

- Predictive workload forecasting  
- Queue velocity tracking  
- Regional trauma mapping  
- Modality distribution analytics  
- AI-generated executive clinical briefings  

**Output:** Data-driven triage prioritization and equipment optimization.

---

### Transplant Intelligence Hub

Organ allocation support module.

- Automated MELD, EPTS, LAS scoring  
- Cold Ischemia Time (CIT) monitoring  
- Organ viability window alerts  
- HLA and blood type matching  
- Logistics simulation (air and ground routing)  

**Output:** Compliance-aligned transplant decision support.

---

### Patient-Centric Communication

Bridging technical diagnostics and patient understanding.

- Radiology terminology translated into plain language  
- Health literacy optimization  
- Structured follow-up guidance  
- Secure patient-clinician communication  

**Output:** Improved clarity, trust, and adherence.

---

### EHR Bridge (FHIR R4)

Interoperability backbone of ScanWise AI.

- Bidirectional FHIR R4 synchronization  
- Mapping to:
  - Problem List  
  - Assessment and Plan  
  - Observations  
  - Procedures  
- Unit normalization  
- ISO-8601 standardization  
- Immutable audit logs  

**Output:** Seamless integration with major EMR systems.

---

## Technical Architecture

| Stack Segment | Technologies |
|--------------|------------|
| Frontend | React 19 |
| AI Engine | Gemini 3 Pro-Preview, Gemini 3 Flash |
| Audio | Gemini 2.5 Flash Native Audio |
| Visualization | Recharts, Tailwind CSS |
| Icons | Lucide React |
| Interoperability | FHIR R4 (HL7 Middleware) |
| Security | End-to-end encryption and anonymization |
| Runtime | Node v2.5 |

---

## Agentic Workflow

1. Ingestion: De-identification and modality detection  
2. Reasoning: Imaging and laboratory correlation  
3. Grounding: Validation against clinical research  
4. Action: Clinical output generation  
5. Integration: FHIR-based EHR update  

---

## Regulatory Positioning

ScanWise AI is a Clinical Decision Support tool.

- Assists licensed healthcare professionals  
- Provides multimodal correlation  
- Does not replace independent clinical judgment  

All transplant allocations must follow national protocols and be validated by certified professionals.

---

## Recent Improvements

### Code Quality
- ESLint pipeline implemented  
- TypeScript errors resolved  
- JSX issues corrected  
- Stable global window handling  

### Stability
- Production build verified  
- Zero lint violations confirmed  
- Deployment-ready environment ensured  

---

## Strategic Differentiation

- Multimodal reasoning across imaging and lab data  
- Integrated transplant intelligence layer  
- Real-time clinical interaction support  
- Dual reporting for clinicians and patients  
- Structured EHR transformation mapping  

---

## License

This project is developed for academic purposes under University Course Project (CS7032).
