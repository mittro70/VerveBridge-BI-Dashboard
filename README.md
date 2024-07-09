# Amazon Sales and Service Performance Analysis

This project involves analyzing Amazon sales and service data to gain insights into sales performance, customer preferences, and service efficiency. The analysis is conducted using two Excel files, and the data is visualized using Power BI.

## Overview

The project follows these main steps:
1. Download the datasets.
2. Data cleaning and preparation.
3. Data analysis using pivot tables.
4. Data visualization using Power BI.

## Datasets

- **Amazon Sale Report - YT.xlsx**
- **amazon-fashion - YT.csv**

## Workflow

1. **Download the Datasets**
   - Download `Amazon Sale Report - YT.xlsx` and `amazon-fashion - YT.csv` from the [following link](https://drive.google.com/file/d/1u-jVqnpG65pR_BtnZ-yMBLJFL4lJLA6G/view).

2. **Data Cleaning and Preparation**
   - **Remove Unnecessary Columns:**
     - Open both Excel files and remove columns that are not required for the analysis.
       - Columns removed: `Style`, `SKU`, `currency`, `ship-postal-code` and `ship-country` from `Amazon Sale Report - YT.xlsx`; `large`, `description`, `product_details`, and `product_url` from `amazon-fashion - YT.csv`.
   - **Fix Typos and Standardize State Names:**
     - In the `ship-state` column, fix any typos and standardise the state names to ensure consistency.

3. **Create Pivot Table**
   - In `Amazon Sale Report - YT.xlsx`, create a pivot table to calculate the percentage of cancelled orders per state.
     - Use the `ship-state` and 'Courier Status' columns in the Rows field.
     - Use Count of `Courier Status` in the Values field.

4. **Load Data to Power BI**
   - Import the cleaned and prepared data from both Excel files into Power BI.
   - Ensure that the data is correctly loaded and relationships between tables are properly defined.

5. **Create Visuals in Power BI**
   - Create visuals to analyze and present the data effectively. The main visuals include:
     - Total Revenue and Quantity Sold.
     - Quantity Sold by Category.
     - Top 10 States by Number of Orders.
     - Courier Status Distribution.
     - Orders Over Time.
     - States with Highest Percentage of Cancelled Couriers.

## Visuals

![dashoard-1](https://github.com/mittro70/VerveBridge-BI-Dashboard/assets/87438903/8bd4447e-a04f-47ad-b646-528f13a4e77e)  
![dashoard-2](https://github.com/mittro70/VerveBridge-BI-Dashboard/assets/87438903/190fe174-515e-4ad6-b4a1-a14f09a644a6)
