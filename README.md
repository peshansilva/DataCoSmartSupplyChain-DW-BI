# BikeShare Data Warehouse & Business Intelligence Solution

## Project Overview

This project presents an end-to-end Data Warehouse and Business Intelligence solution developed using the DataCo dataset.

The solution was designed to support analytical reporting and multidimensional analysis using SQL Server, SSIS, SSAS, OLAP operations, and Power BI.

The project includes ETL pipeline development, dimensional modelling, cube implementation, and interactive business intelligence reporting.

---

## Dataset Information

- Dataset Source: DataCo SMART SUPPLY CHAIN FOR BIG DATA ANALYSIS
- Total records analyzed: Over 180,000+ records
- Data period: 2015 - 2018

The dataset includes:

- Time coverage
- Diverse product categories
- Order scenarios
- Shipping and delivery performance
- Multiple transaction types
- Geographically diverse customer data

---

## Technologies & Tools

- SQL Server
- SQL Server Integration Services (SSIS)
- SQL Server Analysis Services (SSAS)
- SQL Server Management Studio (SSMS)
- Power BI
- Microsoft Excel
- XMLA
- Visual Studio

---

## Data Warehouse Design

A star schema dimensional model was designed and implemented.

### Fact Table
- `Fact_Sales`

### Dimension Tables
- `Dim_Product`
- `Dim_Customer`
- `Dim_Date`

Key concepts implemented:

- Surrogate Keys
- Star Schema Design
- Slowly Changing Dimension (SCD Type 2)
- Role-Playing Dimensions

---

## ETL Pipeline

An ETL pipeline was developed using SSIS to process 12 months of bike-sharing data.

The ETL process included:

- Data extraction from CSV datasets
- Data staging and transformation
- Data cleaning and validation
- Loading dimension tables
- Loading fact tables
- Historical tracking implementation using SCD Type 2

---

## SSAS Cube Implementation

A multidimensional SSAS cube was developed using the DataCo data warehouse.

### Measures
- Sales
- Transaction Process Time
- Quantity


### Hierarchies

- Year → Quater → Month → Day
- Department Name → Category Name → Product Name
- Country → State → City

---

## OLAP Operations Demonstrated

The following OLAP operations were demonstrated using Excel PivotTables connected to the SSAS cube:

- Roll-up
- Drill-down
- Slice
- Dice
- Pivot

---

## Power BI Reports

Four interactive Power BI reports were developed:

1. Matrix Visual Report
2. Cascading Slicers Report
3. Drill-down Analysis Report
4. Drill-through Navigation Report

Features demonstrated:

- Interactive filtering
- Hierarchical drill-down
- Drill-through analysis
- Dynamic slicers
- Multidimensional reporting

---

## Files Included

- `DW-BI-Report.pdf` → Business Intelligence report
- `DW-Report.pdf` → Data Warehouse report
  


---
