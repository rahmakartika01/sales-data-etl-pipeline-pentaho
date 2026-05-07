# sales-data-etl-pipeline-pentaho
ETL data cleaning project using Pentaho Data Integration (PDI)

## Overview
This project focuses on handling missing POSTALCODE values in sales datasets using Pentaho Data Integration (PDI).

The ETL pipeline automatically fills missing postal codes by matching city and state values from supporting datasets.

---

## Tools
- Pentaho Data Integration (PDI)
- ETL Pipeline
- CSV Processing

---

## ETL Process
1. Read sales_data.csv and zipssortedbycitystate.csv
2. Filter rows with NULL postal codes
3. Match city and state using Stream Lookup
4. Replace missing postal code values
5. Merge transformed data
6. Export cleaned dataset into CSV output

---

## Workflow
Upload workflow screenshot here

---

## Skills
- ETL Development
- Data Cleaning
- Data Transformation
- Missing Value Handling
