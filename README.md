# Retail Sales KPI Analysis & Data Quality Assessment

## Project Overview

This project focuses on analyzing retail order data, defining important business KPIs, and assessing data quality using Excel and Python.

The main objective is to create clear KPI definitions and identify data quality issues to support better business decision-making.

## Project Details

* **Project Name:** Retail Sales KPI Analysis & Data Quality Assessment
* **Domain:** Commerce / Retail
* **Decision Owner:** Sales Manager
* **Dataset:** Retail Orders
* **Total Records:** 12
* **Total Columns:** 9

## Tools & Technologies

* Microsoft Excel
* Python
* Pandas
* Jupyter Notebook
* GitHub

## Project Deliverables

### 1. KPI Dictionary

Defines important business KPIs, including:

* Total Revenue
* Total Orders
* Average Order Value
* Total Quantity Sold
* Average Discount
* Paid Orders
* Pending Orders
* Payment Success Rate

### 2. Data Quality Profile

Uses Python and Pandas to examine:

* Missing values
* Duplicate records
* Duplicate Order IDs
* Invalid dates
* Negative quantities
* Invalid quantity formats
* Invalid discount percentages
* Inconsistent category and payment status values

### 3. Data Quality Contract

Defines data validation rules, expected values, quality thresholds, and actions for handling invalid records.

## Dataset Information

The dataset contains retail order information such as:

* Order ID
* Order Date
* Customer Segment
* City
* Product Category
* Quantity
* Unit Price
* Discount Percentage
* Payment Status

## Key Findings

The initial dataset contains:

* 12 records and 9 columns
* 3 missing values
* 1 duplicate record
* 1 duplicate Order ID
* 1 invalid date
* 1 negative quantity
* 1 invalid quantity format
* 1 invalid discount percentage

## Project Structure

```text
Retail-Sales-KPI-Project/
│
├── 01_Dataset/
│   ├── retail-orders-raw.csv
│   └── retail-data-dictionary.csv
│
├── 02_KPI_Dictionary/
│   └── Retail_KPI_Workbook.xlsx
│
├── 03_Data_Quality_Profile/
│   ├── Data_Quality_Profile.ipynb
│   └── Retail_Data_Quality_Summary.csv
│
├── 04_Data_Quality_Contract/
│   └── Data_Quality_Contract.xlsx
│
└── README.md
```

## Conclusion

This project demonstrates the importance of KPI definitions and data quality validation in retail analytics. It helps identify data issues and establish consistent rules for reliable business reporting.

---

**Created by:** L. Suvetha
**Domain:** Commerce / Retail Analytics
