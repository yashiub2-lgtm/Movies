# 🎬 IMDB Movies & Global Demographics Dashboard

> **Note on Publishing:** Because the `.pbix` file exceeds 1 GB, it cannot be published to a free Power BI workspace and requires a Power BI Pro (paid) license to share/publish online.

---

## 📌 Overview

An interactive Power BI dashboard visualizing the global distribution of movie and TV content using the IMDB Non-Commercial Dataset combined with detailed regional demographics.

While the frontend features a rich geospatial interface, **the core focus of this project is a robust backend data architecture**—featuring custom data schemas, advanced ETL pipelines, and the seamless integration of multiple disparate data sources to build a rock-solid foundation for visualization.

---

## ⚙️ Backend & Data Engineering Focus

The primary engineering effort went into solving complex data integration challenges:

* **Multi-Source Integration:** Successfully ingested, cleaned, and joined data from **3 distinct sources**, including official government web portals (for latest regional/zip data) and Kaggle datasets.
* **Data Schema & Modeling:** Designed a scalable star/snowflake schema optimized for cross-filtering across millions of records.
* **ETL Pipelines:** Built efficient Power Query transformation pipelines to handle data cleansing, type handling, and relationship mapping between movie production data and geographic/demographic attributes.

---

## 📊 Features

* **Azure Maps Bubble Visualization:** Dynamic geospatial mapping of film and television production across countries.
* **Interactive Filters:** Granular filtering by decade, title type, and continent to explore historical trends.
* **Enriched Tooltips:** Country-level demographic insights (median age, primary language, religion, and currency).
* **Optimized Aggregations:** Distinct title count calculations structured for high-performance reporting.

---

## 🗂 Data Sources

1. **IMDB Non-Commercial Dataset:** Core movie and TV show titles, genres, release years, and country credits.
2. **Government Portal Data:** Official geographic and regional codes (e.g., zip/postal and boundary data).
3. **Kaggle Datasets:** Supplementary demographic and economic indicators (median age, languages, religion, and currencies by country).

---

## 🔎 Key Insights

* Content production is heavily concentrated in a select few major hubs globally.
* Developing regions across Africa, Central Asia, and Pacific territories exhibit lower representation in mainstream datasets.
* Significant, measurable growth has occurred in Asian markets over recent decades.

---

## 🛠 Tech Stack

* **Data Engineering & Modeling:** Power Query, Advanced ETL, Multi-source data integration
* **Visualization & BI:** Microsoft Power BI, Azure Maps
* **Data Sources:** IMDB, Government Datasets, Kaggle
