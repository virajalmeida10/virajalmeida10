<div align="center">

<!-- HEADER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=140&section=header&text=&fontSize=0&animation=fadeIn" />

<!-- DYNAMIC TYPING INTRO -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3500&pause=800&color=4FC3F7&center=true&vCenter=true&width=700&lines=Hi+there%2C+I'm+%5BYour+Viraj Almeida%5D+%F0%9F%91%8B;Data+Engineer+%7C+Lakehouse+Architect;Building+pipelines+that+scale+to+millions;Turning+raw+data+into+business+clarity)](https://git.io/typing-svg)

<br/>

<!-- PROFILE VIEWS + FOLLOWERS -->
![Profile Views](https://komarev.com/ghpvc/?username=virajalmeida10&style=flat-square&color=4FC3F7&label=Profile+Views)
[![GitHub followers](https://img.shields.io/github/followers/virajalmeida10?style=flat-square&color=4FC3F7&labelColor=1a1a2e)](https://github.com/virajalmeida10)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/YOUR_PROFILE)

</div>

---

## ⚡ About Me

```python
engineer = {
    "name"        : "Viraj Almeida",
    "role"        : "Data Engineer",
    "location"    : "New Jersey, United States",
    "focus"       : ["Lakehouse Architecture", "Real-time Pipelines", "Cloud Data Platforms"],
    "currently"   : "Building end-to-end hotel data pipelines on Databricks",
    "learning"    : ["Delta Live Tables", "Apache Iceberg", "dbt Advanced Patterns"],
    "open_to"     : "Interesting data engineering challenges",
    "fun_fact"    : "I think in medallion architecture — bronze, silver, gold, always."
}
```

> I design and build **end-to-end data pipelines** that bridge raw operational data and high-quality analytical assets. My work spans ingestion, transformation, orchestration, and serving — with a strong emphasis on data quality, reliability, and cost-efficiency on cloud lakehouse platforms.

---

## 🏗️ Featured Project — Hotel Data Lakehouse

<table>
<tr>
<td width="60%">

### `databricks-lakehouse-hotel` 🏨

A **production-grade lakehouse pipeline** built on Databricks, processing hotel operations data across the full medallion architecture — from raw CDC events to curated, business-ready analytics.

**What it does:**
- Ingests booking, reservation, revenue, and guest data from multiple source systems
- Implements full **medallion architecture** (Bronze → Silver → Gold) using Delta Lake
- Orchestrates multi-layer transformations with **Apache Spark** on Databricks clusters
- Applies **SCD Type 2** logic for slowly-changing dimension tracking across properties
- Delivers clean, aggregated datasets to downstream BI and ML consumers

**Outcomes:**
- Unified data model spanning hundreds of hotel properties
- Incremental processing with Delta Lake time-travel for full auditability
- Reusable transformation modules with parameterized notebooks

</td>
<td width="40%" align="center">

```
📦 RAW SOURCES
    │
    ▼
┌─────────────┐
│   BRONZE    │  ← Raw ingest, CDC
│  Delta Lake │    immutable, append
└──────┬──────┘
       │
       ▼
┌─────────────┐
│   SILVER    │  ← Cleansed, typed
│  Delta Lake │    deduplicated
└──────┬──────┘
       │
       ▼
┌─────────────┐
│    GOLD     │  ← Aggregated KPIs
│  Delta Lake │    BI / ML ready
└─────────────┘
```

</td>
</tr>
</table>

**Key Tech:** `Databricks` `Apache Spark` `Delta Lake` `PySpark` `SQL` `Azure Data Factory` `Python`

[![View Repo](https://img.shields.io/badge/View_Repository-4FC3F7?style=for-the-badge&logo=github&logoColor=black)](https://github.com/YOUR_USERNAME/databricks-lakehouse-hotel)

---

## 🛠️ Tech Stack

<details open>
<summary><b>Data Engineering & Platforms</b></summary>
<br/>

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=flat-square&logo=databricks&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)

</details>

<details open>
<summary><b>Cloud & Storage</b></summary>
<br/>

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure Data Lake](https://img.shields.io/badge/ADLS_Gen2-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

</details>

<details open>
<summary><b>Languages & Databases</b></summary>
<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

</details>

<details open>
<summary><b>DevOps & Tools</b></summary>
<br/>

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</details>

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=4FC3F7&icon_color=4FC3F7&text_color=c9d1d9&count_private=true" />
&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=4FC3F7&text_color=c9d1d9&langs_count=6" />

<br/><br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=tokyonight&hide_border=true&background=0d1117&ring=4FC3F7&fire=4FC3F7&currStreakLabel=4FC3F7)](https://git.io/streak-stats)

</div>

---

## 🧠 Engineering Philosophy

<table>
<tr>
<td align="center" width="25%">

**🔁 Idempotency First**
<br/>Every pipeline I build runs safely on retry. No surprises.

</td>
<td align="center" width="25%">

**🥇 Medallion by Default**
<br/>Bronze → Silver → Gold. Clean separation of concerns, always.

</td>
<td align="center" width="25%">

**📏 Schema as Contract**
<br/>Data contracts and schema evolution are engineering, not afterthoughts.

</td>
<td align="center" width="25%">

**🔍 Observability Built In**
<br/>If I can't measure pipeline health, I haven't finished the job.

</td>
</tr>
</table>

---

## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_PROFILE)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:you@email.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_USERNAME)
[![Resume](https://img.shields.io/badge/Resume-4FC3F7?style=for-the-badge&logo=adobeacrobatreader&logoColor=black)](https://YOUR_RESUME_LINK)

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=80&section=footer" />

*"Data pipelines are plumbing. Good engineers make the water run clean."*

</div>
