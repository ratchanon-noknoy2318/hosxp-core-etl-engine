# HOSxP Core ETL Engine

<p align="center">
  <img src="https://img.shields.io/badge/Data%20Engineer-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Healthcare%20Data%20Platform-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/HOSxP%20System-111111?style=flat-square" />
</p>

---

## Overview

This project is a healthcare data engineering pipeline designed to extract, interpret, and transform data from a legacy HOSxP hospital information system into structured, analysis-ready datasets.

The system operates in a low-documentation environment where data understanding relies on schema exploration, domain collaboration, and iterative SQL-based investigation.

---

## Problem Statement

Hospital operational data stored in HOSxP presents several challenges:

- Complex relational database structure with 50+ tables
- Limited documentation of clinical meaning at field level
- Fragmented understanding between technical schema and clinical workflows
- High dependency on manual interpretation for reporting and analysis

These limitations reduce efficiency in healthcare reporting and data-driven decision-making.

---

## Objectives

The primary objectives of this project are:

- Extract relevant clinical and operational data from HOSxP
- Translate raw database structures into meaningful healthcare concepts
- Establish a repeatable data investigation and transformation workflow
- Enable structured datasets for downstream reporting and analytics use cases
- Improve alignment between technical data structures and clinical workflows

---

## Data Engineering Approach

### Domain Understanding
- Collaborated with healthcare staff to understand operational and clinical workflows
- Identified key concepts such as patient flow, clinical events, and timing-based measurements

### Schema Exploration
- Analyzed HOSxP relational schema
- Mapped relationships across multiple tables and modules
- Identified primary keys, foreign keys, and implicit business logic

### SQL-Based Investigation
- Performed iterative SQL querying to validate hypotheses
- Cross-referenced multiple data sources for consistency checks
- Refined understanding of ambiguous fields through repeated exploration

### LLM-Assisted Analysis
- Used LLM tools to support schema interpretation
- Generated alternative hypotheses for unclear data structures
- Accelerated exploration of complex relational dependencies

### Domain Validation
- Validated interpretations with healthcare professionals
- Ensured extracted data aligned with real-world clinical operations

---

## Data Flow Architecture

HOSxP Legacy Database  
→ SQL Extraction Layer  
→ Data Cleaning and Transformation Layer  
→ Structured Healthcare Datasets  
→ Reporting and Analytics Layer  

---

## Tech Stack

- SQL
- HOSxP Hospital Information System
- Data Modeling and Schema Analysis
- Healthcare Domain Collaboration
- LLM-assisted Data Investigation

---

## Key Engineering Concepts

- Domain-driven data modeling
- Iterative schema discovery
- Hypothesis-driven SQL exploration
- Data validation through domain experts
- Bridging healthcare operations and data systems

---

## Outcomes

- Improved interpretability of legacy hospital data structures
- Established repeatable methodology for healthcare data extraction
- Enabled structured datasets for operational reporting use cases
- Reduced ambiguity in clinical data interpretation
- Supported foundation for future healthcare data platform development

---

## Notes

This system operates under real-world healthcare constraints, including:

- Incomplete documentation of legacy systems
- High complexity of relational healthcare data
- Strong dependency on domain expertise for correct interpretation
- Requirement for iterative validation and refinement of assumptions
