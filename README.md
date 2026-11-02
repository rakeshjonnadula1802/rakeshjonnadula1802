# 👋 Hi, I'm Rakesh Jonnadula

### Azure Data Engineer | Databricks | PySpark | ETL/ELT | Lakehouse | Big Data

<p align="left">
  <img src="https://img.shields.io/badge/Azure-Data%20Engineering-blue" />
  <img src="https://img.shields.io/badge/Databricks-Lakehouse-red" />
  <img src="https://img.shields.io/badge/PySpark-Big%20Data-orange" />
  <img src="https://img.shields.io/badge/Python-Development-yellow" />
  <img src="https://img.shields.io/badge/SQL-Data%20Engineering-blue" />
  <img src="https://img.shields.io/badge/Delta%20Lake-Data%20Lakehouse-purple" />
</p>

---

## 👨‍💻 About Me

I am a **Data Engineer with 1+ years of experience** specializing in building scalable **ETL/ELT pipelines, Azure cloud data platforms, Lakehouse solutions, and Big Data processing workflows**.

My core expertise includes **Azure Data Factory, Azure Databricks, PySpark, Apache Spark, Spark SQL, Delta Lake, and ADLS Gen2**.

I focus on developing **reliable, scalable, secure, and performance-optimized data solutions**, with hands-on experience in **Medallion Architecture, incremental processing, data quality, data governance, data modeling, and CI/CD**.

I have optimized cloud data workloads by implementing incremental processing and Spark performance techniques, achieving approximately **25% reduction in cloud compute costs** and **30% improvement in Spark query runtimes**.

---

## 🧰 Technical Skills

### ☁️ Azure & Cloud Data Engineering

<p>
<img src="https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Azure%20Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" />
<img src="https://img.shields.io/badge/ADLS%20Gen2-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Azure%20SQL-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Azure%20Synapse-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Azure%20Key%20Vault-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
</p>

**Azure Data Factory • Azure Databricks • ADLS Gen2 • Azure SQL • Azure Synapse • Azure Logic Apps • Azure Key Vault**

### ⚡ Big Data & Processing

<p>
<img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
<img src="https://img.shields.io/badge/Delta%20Lake-00ADD8?style=for-the-badge" />
</p>

**Apache Spark • PySpark • Spark SQL • Delta Lake • Auto Loader • Incremental Processing • Medallion Architecture**

### 💻 Programming & Databases

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

**Python • PySpark • SQL • MySQL • Azure SQL**

### 🔐 Data Governance & Security

**Unity Catalog • Data Governance • Data Quality • Schema Validation • Access Policies • Managed Identities • Azure Key Vault**

### 🔄 Development & Tools

**Git • CI/CD • Visual Studio Code • Jira • Power BI**

---

# 💼 Professional Experience

## Data Engineer — Teleperformance

**Chennai, India | Aug 2025 – Present**

- Developed **end-to-end ETL/ELT pipelines** using Azure Data Factory, Databricks, PySpark, Spark SQL, ADLS Gen2, and Delta Lake.
- Designed **dynamic and parameterized ADF pipelines** with incremental processing, reducing unnecessary full loads and cloud compute costs by approximately **25%**.
- Developed scalable **PySpark and Spark SQL transformations** for cleansing, standardization, joins, aggregations, and data modeling.
- Optimized Apache Spark workloads using **partition pruning, broadcast joins, and caching**, reducing query runtimes by approximately **30%**.
- Implemented data-quality validation covering **duplicates, null values, schema drift, and record reconciliation**.
- Applied **Unity Catalog** for centralized data governance, data discovery, access policies, and granular permissions.
- Integrated **Azure Key Vault and Managed Identities** to secure data engineering workflows and eliminate hardcoded credentials.
- Used **Git** for version control, code reviews, CI/CD, and Dev/QA/Production deployments.

---

## AI Training Specialist — Contract | Outlier.ai

**2024 – 2025**

- Validated and refined large-scale datasets and code-generation outputs.
- Applied **RLHF, data validation, anomaly detection, and schema compliance** techniques.
- Collaborated with distributed engineering teams to identify data-quality issues and reduce output error rates by **18%+**.

---

# 🚀 Featured Project

## Metadata-Driven Data Engineering Framework

**Databricks • PySpark • SQL • Delta Lake • Unity Catalog • Azure Data Factory**

A scalable **metadata-driven ETL framework** designed using **Databricks and Medallion Architecture** to support automated, incremental, and governed data processing.

### 🏗️ Architecture

```text
                    ┌──────────────────────┐
                    │    Source Systems    │
                    │ SQL Server / Storage  │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Azure Data Factory │
                    │   Orchestration      │
                    └──────────┬───────────┘
                               │
                               ▼
                 ┌─────────────────────────────┐
                 │        DATABRICKS           │
                 │     Metadata-Driven ETL     │
                 └─────────────┬───────────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
        ┌──────────┐     ┌──────────┐     ┌──────────┐
        │  BRONZE  │ ──▶ │  SILVER  │ ──▶ │   GOLD   │
        │   Raw    │     │ Cleansed │     │ Business │
        │   Data   │     │   Data   │     │   Data   │
        └──────────┘     └──────────┘     └──────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │    Unity Catalog     │
                    │ Governance & Access  │
                    └──────────────────────┘
```

### 🔑 Key Capabilities

- Built **Bronze/Silver/Gold Medallion Architecture** for scalable ingestion and transformation.
- Developed reusable **PySpark and Auto Loader pipelines** for automated incremental ingestion.
- Implemented metadata-driven orchestration using **Databricks Jobs/Workflows and Azure Data Factory**.
- Designed parameterized processing for **multi-table data pipelines**.
- Added **audit logging, monitoring, error handling, and automated failure notifications**.
- Developed Silver and Gold transformations using **PySpark and SQL**.
- Applied **Unity Catalog** for centralized governance and access management.

---

# 📊 Data Engineering Focus

```text
                 DATA ENGINEERING
                        │
          ┌─────────────┴─────────────┐
          │                           │
     DATA INGESTION              PROCESSING
          │                           │
    Azure Data Factory          PySpark / Spark
    Auto Loader                 Spark SQL
          │                           │
          └─────────────┬─────────────┘
                        │
                   DELTA LAKE
                        │
              MEDALLION ARCHITECTURE
                        │
          ┌─────────────┼─────────────┐
          │             │             │
       BRONZE         SILVER        GOLD
          │             │             │
          └─────────────┼─────────────┘
                        │
                 DATA GOVERNANCE
                        │
                  UNITY CATALOG
```

---

# 🎯 Core Strengths

| Area | Expertise |
|---|---|
| **Cloud** | Microsoft Azure |
| **ETL/ELT** | Azure Data Factory, Databricks |
| **Big Data** | Apache Spark, PySpark, Spark SQL |
| **Lakehouse** | Delta Lake, Medallion Architecture |
| **Storage** | ADLS Gen2 |
| **Databases** | Azure SQL, MySQL, Azure Synapse |
| **Programming** | Python, PySpark, SQL |
| **Governance** | Unity Catalog, Data Quality, Data Governance |
| **Security** | Azure Key Vault, Managed Identities |
| **DevOps** | Git, CI/CD |
| **Analytics** | Power BI |

---

# 📚 Education

### Bachelor of Technology — Computer Science and Technology

**Presidency University, Bangalore, India | 2024**

---

## 📫 Contact

📍 **Chennai, India**

📧 **rakeshjonnadula180@gmail.com**

📞 **+91 9032813143**

---

<p align="center">

### ⭐ Building scalable data solutions with Azure, Databricks & PySpark

**Thanks for visiting my profile!**

</p>
