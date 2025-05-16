# healthcare-data-warehouse-using-power-bi
In this I am simulating an end to end healthcare data warehouse using SQL server and SSIS for ETL and power BI for reporting. Here we will design a star schema transform raw and claims data and create business dashboards

# Healthcare Data Warehouse with SQL, SSIS, and Power BI

This project simulates a healthcare data warehousing solution using **SQL Server**, **SSIS** for ETL, and **Power BI** for visualization.

## 📌 Features
- Star schema: FactClaim, DimPatient, DimProvider
- ETL using SSIS to transform & load data from CSV
- Power BI dashboard for interactive insights

## 🛠 Tech Stack
- SQL Server 2019
- SSIS (SQL Server Integration Services)
- Power BI Desktop
- CSV

## 📊 Power BI Dashboard
![Power BI Dashboard](screenshots/powerbi_dashboard.png)

## 🚀 How to Use
1. Run SQL scripts in `SQL/` to set up schema and sample data
2. Use SSIS package in `ETL/` to load CSV into `FactClaim`
3. Open `.pbix` in Power BI and refresh data source

## 📁 Folder Structure
- `ETL/`: SSIS package
- `SQL/`: Schema and data SQL scripts
- `Data/`: Raw data
- `Reports/`: Power BI `.pbix` file
- `screenshots/`: Visual output
