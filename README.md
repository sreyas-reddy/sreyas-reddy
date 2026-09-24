# Sreyas Reddy

**Data Engineer | Data Quality & Governance | AWS & Snowflake**

📍 Milwaukee, WI · ✉️ sreyasreddy.data@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/sreyasreddy01)

---

## About

Data Engineer with 5+ years of experience strengthening the reliability, traceability, and control of banking data across lending, servicing, and finance reporting. I build and govern AWS and Snowflake pipelines with reconciliation, control totals, exception handling, dbt tests, lineage, business definitions, and role-based access — progressing from hands-on ETL development to ownership of data models, quality controls, governance enablement, and release readiness.

**Selected impact:** 300K loan accounts supported daily · 18M repayment records migrated · nightly refresh reduced 31% · validation failures cut from 2.6% to 0.9%

---

## Experience

**Data Engineer — Fiserv** · Milwaukee, WI · *Jan 2026 – Present*
- Maintain restartable AWS Glue pipelines for 4 daily S3 servicing feeds, loading Snowflake for 300,000 loan accounts by the 7:00 a.m. reporting deadline
- Block refreshes of 12 operations reports when Snowflake quality gates detect duplicate account/date keys or payment-allocation discrepancies
- Prototype statement extraction with Azure AI Document Intelligence + Azure OpenAI; schema and date fixes raised field-level exact-match accuracy from 88% to 94% across 200 held-out statements

**Senior Data Engineer — Mphasis** · Bengaluru, India · *Jul 2023 – May 2024*
- Standardized ownership and business definitions for 36 banking datasets, aligning outstanding-principal and overdue-balance calculations across finance and operations
- Reduced median nightly refresh 31% (210 → 145 min) through incremental extraction, Glue partition pruning, and Snowflake query tuning
- Published definitions, dbt lineage, and source-to-target mappings for 18 critical data elements; administered 3 Snowflake access tiers with role-based grants and restricted views

**Data Engineer — Mphasis** · Bengaluru, India · *Jan 2022 – Jun 2023*
- Migrated 1.2M customer records and 18M repayment transactions into Snowflake via S3 and Glue; cut initial validation failures from 2.6% to 0.9% in 6 months
- Built exception tables with rule IDs, source keys, and batch identifiers feeding idempotent Snowflake MERGE reloads without duplication

**Data Engineer — Nucleus Software** · Noida, India · *Aug 2019 – Dec 2021*
- Built Informatica PowerCenter mappings and Oracle SQL transformations for 10 daily lending feeds
- Reduced batch-rerun preparation time 60% (75 → 30 min) with audit tables, staging validation, and duplicate-safe updates

---

## Projects

### [AI-Assisted Data Contract Monitor](https://github.com/sreyas-lankala/ai-data-contract-monitor)
`Python` `dbt` `Snowflake` `Airflow` `Azure OpenAI`

Metadata-driven checker that compares incoming schemas, freshness, and key constraints against versioned data contracts, routes violations to exception tables, and drafts plain-language impact summaries for review. Deterministic SQL and dbt tests plus JSON schema validation around LLM output keep pass/fail controls independent of AI-generated explanations.

### [Privacy-Aware Synthetic Banking Data Lab](https://github.com/sreyas-lankala/synthetic-banking-data-lab)
`Python` `Snowflake` `dbt`

Synthetic loan and repayment datasets that preserve referential integrity and edge cases for duplicate payments, late fees, and missing accounts — with zero production PII. Automated scorecards for completeness, uniqueness, validity, and reconciliation so test data is checked against governance rules before pipeline runs.

---

## Tech Stack

**Data Quality & Controls**
![SQL](https://img.shields.io/badge/SQL-025E8C?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square)

**Cloud & Platforms**
![Snowflake](https://img.shields.io/badge/Snowflake-29B5D5?style=flat-square)
![AWS Glue](https://img.shields.io/badge/AWS_Glue-FF9900?style=flat-square)
![Amazon S3](https://img.shields.io/badge/Amazon_S3-569A31?style=flat-square)
![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square)
![Informatica](https://img.shields.io/badge/Informatica-FF4D00?style=flat-square)

**Governance & AI**
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat-square)
![Azure AI](https://img.shields.io/badge/Azure_AI_Document_Intelligence-0078D4?style=flat-square)

---

## Education & Certifications

- 🎓 **M.S. Computer Science** — Concordia University Wisconsin (2024–2026)
- 🎓 **B.Tech, Mechanical Engineering** — JNTU Hyderabad (2015–2019)
- 🏅 **AWS Certified Data Engineer – Associate** (2026)
- 🏅 **Snowflake SnowPro Core** (2026)
