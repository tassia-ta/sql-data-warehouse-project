# Data Warehouse & Analytics Project

## Project Overview

This project demonstrates the development of an end-to-end data warehouse solution, covering data ingestion, transformation, dimensional modeling, data quality validation, and analytics.

The project was developed as part of my Data Engineering portfolio to demonstrate practical experience with SQL, ETL/ELT concepts, dimensional modeling, Medallion Architecture, and analytical data preparation.

## Data Engineering Workflow

1. Source data ingestion
2. Raw data storage
3. Data cleaning and standardization
4. Data quality validation
5. Data transformation
6. Dimensional modeling
7. Creation of fact and dimension tables
8. Analytical SQL queries and reporting

## Technologies

- SQL
- SQL Server
- SSMS
- Git / GitHub
- Draw.io
- Dimensional Modeling
- ETL / ELT
- Medallion Architecture

## Architecture

The data architecture for this project follows the Medallion Architecture with **Bronze, Silver, and Gold layers**.

<img width="6235" height="3216" alt="image" src="https://github.com/user-attachments/assets/48d684c3-a7ed-4321-9ce2-5807733d16c2" />

1. **Bronze Layer:** Stores raw data as-is from the source systems. Data is ingested from CSV files into the SQL Server database.
2. **Silver Layer:** Cleaned and standardized data. This layer includes data cleansing, standardization, and normalization processes
to prepare data for analysis.
3. **Gold Layer:** Business-ready dimensional models. Houses business-ready data modeled into a star schema required for reporting
and analytics.

## Repository Structure
```
data-warehouse-project/
│
├── datasets/                       # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                           # Project documentation and architecture details
│   ├── etl.drawio                  # Draw.io file showing ETL techniques and methods
│   ├── data_architecture.drawio    # Draw.io file showing the project's architecture
│   ├── data_catalog.md             # Catalog of datasets, field descriptions, and metadata
│   ├── data_flow.drawio            # Draw.io file for the data flow diagram
│   ├── data_models.drawio          # Draw.io file for data models (star schema)
│   └── naming-conventions.md       # Naming guidelines for tables, columns, and files
│
├── scripts/                        # SQL scripts for ETL and transformations
│   ├── bronze/                     # Scripts for extracting and loading raw data
│   ├── silver/                     # Scripts for cleaning and transforming data
│   └── gold/                       # Scripts for creating analytical models
│
├── tests/                          # Test scripts and data quality files
│
├── README.md                       # Project overview and instructions
├── LICENSE                         # License information for the repository
├── .gitignore                      # Files and directories ignored by Git
└── requirements.txt                # Dependencies and requirements for the project
```
## License

This project is licensed under the MIT License

---
