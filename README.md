# Coimbatore Retail Sales Analysis & Dashboard

## Project Overview

This project focuses on combining and analysing sales data from three different retail store systems (Store A, Store B and Store C) for a fictional Coimbatore retail chain.

The objective is to clean, standardise, combine and analyse approximately 15,000 sales records using Microsoft Excel and Power Query, and create an interactive dashboard for monthly business performance reviews.

## Project Folder Structure

```text
Coimbatore_Retail_Sales_Analysis/
│
├── 01_Raw_Data/
│   ├── Store_A
│   ├── Store_B
│   └── Store_C
│
├── 02_Cleaned_Data/
│   ├── Store_A_Cleaned
│   ├── Store_B_Cleaned
│   └── Store_C_Cleaned
│
└── 03_Combined_Data/
    ├── Combined_Analysis.xlsx
    └── Dashboard.png
```

**Note:** Cleaning logs and documentation explaining the cleaning process are available inside `02_Cleaned_data`.

## Folder Description

### 01_Raw_data
Contains the original, unmodified sales exports from all three store systems:

- Store A
- Store B
- Store C

These files serve as the source data for the project.

### 02_Cleaned_data
Contains the individually cleaned datasets for Store A, Store B and Store C.

This folder also includes the data cleaning logs and documentation explaining:

- Data cleaning procedures.
- Handling of missing values and duplicates.
- Standardisation of product and region names.
- Date and currency format corrections.
- Return transaction handling.
- Lookup tables and standardisation rules.
- Data quality checks and cleaning limitations.

### 03_Combined_data
Contains the final combined sales dataset created by appending the three cleaned store datasets using Power Query.

It also includes:

- Final Excel workbook with Pivot Tables, analysis and dashboard.
- Dashboard.png – exported screenshot of the final dashboard.

## Tools & Technologies

- Microsoft Excel
- Power Query
- Pivot Tables
- Pivot Charts
- Excel Slicers
- Excel Formulas
- Data Validation and Reconciliation

## Key Analysis

The project covers:

1. Sales analysis by region.
2. Sales analysis by category.
3. Sales analysis by store.
4. Product-wise sales and profit.
5. Monthly sales trends.
6. Profit and profit margin analysis.
7. Units sold analysis.
8. Month-on-Month (MoM) growth.
9. Year-on-Year (YoY) growth.
10. Return transaction analysis.

## Dashboard

The interactive Excel dashboard provides an overview of key performance indicators, sales trends, profitability and store performance.

It includes filters for Year, Region and Store to support interactive business analysis.

## Project Objective

To develop a repeatable Excel-based data cleaning and reporting process that transforms inconsistent sales exports into a standardised dataset and provides meaningful business insights for monthly management reviews.
