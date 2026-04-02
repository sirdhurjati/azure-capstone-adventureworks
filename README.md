# Azure Data Engineering Capstone — AdventureWorksDW2019

## Overview
End-to-end Azure Data Engineering project built using the AdventureWorksDW2019 dataset. 
This project covers the full data pipeline lifecycle from ingestion to visualisation, 
including historical and incremental load strategies, cloud storage, ETL orchestration, 
and business intelligence reporting.

## Architecture
SQL Server (SSMS) → Azure DevOps → Azure Data Factory → ADLS → Databricks → Power BI

## Tech Stack
- Azure Data Factory (ADF) — pipeline orchestration
- Azure Data Lake Storage (ADLS) — cloud storage
- Azure Databricks — data transformation using PySpark and Delta tables
- Azure DevOps — version control for ETL scripts and notebooks
- SQL Server & SSMS — source data and staging
- Azure Data Studio — query development and testing
- Power BI — dashboard and reporting

## Key Features
- Historical and incremental load pipelines built and deployed in ADF
- Databricks notebooks for ETL — Parquet ingestion, data cleaning, Delta table MERGE
- Watermark based incremental loading strategy
- Six Power BI visualisations including Customer Demographics Overview
- Full debugging and troubleshooting of schema mismatches and pipeline failures
- All scripts version controlled via Azure DevOps

## Power BI Dashboard
Customer Demographics Overview includes:
- Customers by Gender
- Customers by English Occupation
- Marital Status vs Number of Children
- Average Yearly Income by English Education
- Home Ownership vs Income
- Map: Customers by Region

## Author
Siri Chandana Dhurjati
QA Engineer | Data Engineer | MSc Computer Science — Teesside University
