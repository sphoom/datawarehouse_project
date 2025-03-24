# Data Warehouse Project

## Project Overview
This project implements a comprehensive data warehouse solution for a retail business, following the medallion architecture (bronze, silver, gold layers). The solution includes data ingestion, cleaning, transformation, and visualization to support business intelligence and decision making.

## Business Objectives
- Track and analyze sales performance across regions and product categories
- Identify top customers and their purchasing patterns
- Monitor inventory levels and optimize stock allocation
- Analyze customer churn and retention rates
- Generate actionable insights for business growth

## Technical Architecture
This project follows a modern data engineering approach with:

- **Bronze Layer**: Raw data ingestion with metadata tracking
- **Silver Layer**: Cleaned and structured data with enforced relationships
- **Gold Layer**: Analytical models optimized for business reporting
- **Reporting Layer**: Interactive Power BI dashboards

![Data Warehouse Architecture](docs/architecture_diagram.png)

## Project Structure
```
/
├── sql/
│   ├── bronze/       # Raw data ingestion scripts
│   ├── silver/       # Data cleaning and standardization
│   └── gold/         # Star schema for analytics
├── etl_scripts/      # Python ETL scripts
├── powerbi/          # Power BI dashboard files
├── tests/
│   └── data_quality/ # Data quality validation tests
├── .github/
│   └── workflows/    # CI/CD pipelines for testing
├── docs/             # Project documentation
│   └── data_dictionary.md
└── README.md
```

## Implementation Progress
- [x] Phase 1: Project Setup (Completed)
- [ ] Phase 2: Bronze Layer – Raw Data Ingestion (In Progress)
- [ ] Phase 3: Silver Layer – Cleaned & Structured Data
- [ ] Phase 4: Data Quality Checks
- [ ] Phase 5: Gold Layer – Analytics Model
- [ ] Phase 6: Reporting Layer – Power BI Dashboard
- [ ] Phase 7: Documentation & Presentation

## Key Features
- Incremental data loading with metadata tracking
- Automated data quality validation
- Star schema optimized for BI reporting
- Interactive Power BI dashboards
- CI/CD integration with GitHub Actions

## Tech Stack
- **Data Storage**: SQL Server/PostgreSQL
- **ETL Processing**: Python, SQL
- **Data Quality**: Custom SQL-based testing framework
- **Visualization**: Power BI
- **Version Control**: Git/GitHub
- **CI/CD**: GitHub Actions

## Getting Started
1. Clone this repository
2. Follow installation instructions in [setup.md](docs/setup.md)
3. Run the ETL pipeline to populate the data warehouse
4. Open the Power BI dashboard to explore the data

## Documentation
- [Data Dictionary](docs/data_dictionary.md)
- [Setup Guide](docs/setup.md)
- [ETL Pipeline](docs/etl_pipeline.md)

## Future Enhancements
- Add data lineage tracking
- Implement real-time data ingestion
- Add machine learning models for predictive analytics

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
