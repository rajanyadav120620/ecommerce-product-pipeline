# E-Commerce Product Data Pipeline

## Project Overview

This project demonstrates an end-to-end Data Engineering pipeline that extracts product data from a real-world WooCommerce API, performs data cleaning and transformation, and prepares the data for analytics and reporting.

The goal of this project is to simulate a real-world Data Engineering workflow involving data ingestion, processing, feature engineering, and storage using Python and data engineering best practices.

## Business Problem

E-commerce companies generate large volumes of product data from websites and APIs. This data often contains nested JSON structures, missing values, and inconsistent formats that need to be processed before analysis.

This project automates the process of:

* Extracting product data from an API
* Converting JSON data into a structured format
* Cleaning and validating data
* Creating business metrics such as discounts and discount percentages
* Preparing data for reporting and analytics

## Technology Stack

* Python
* Pandas
* Requests
* Jupyter Notebook
* Git & GitHub

Future Enhancements:

* PySpark
* PostgreSQL
* Apache Airflow
* AWS S3
* Power BI

## Data Source

WooCommerce Product API

The dataset is collected from a live WooCommerce Store API that returns product information in JSON format.

## Project Architecture

API
→ Data Extraction
→ Raw Data Storage
→ Data Cleaning
→ Data Transformation
→ Feature Engineering
→ Processed Dataset
→ Analytics & Reporting

## Project Workflow

### Step 1: Data Extraction

* Connect to WooCommerce API
* Retrieve product data in JSON format
* Store raw data for future processing

### Step 2: Data Validation

* Check for missing values
* Verify data types
* Analyze data quality

### Step 3: Data Cleaning

* Remove unnecessary columns
* Handle null values
* Standardize field names

### Step 4: Feature Engineering

Create business metrics:

* Discount Amount
* Discount Percentage

### Step 5: Data Storage

* Save raw data as CSV
* Save cleaned data as CSV
* Prepare data for database loading

## Folder Structure

ecommerce-product-pipeline/

├── data/

│ └── raw_products.csv

├── output/

│ └── clean_products.csv

├── notebooks/

│ └── 01_extract_data.ipynb

├── scripts/

├── README.md

└── requirements.txt

## Key Features

* API Data Ingestion
* JSON Processing
* Data Cleaning
* Data Transformation
* Feature Engineering
* CSV Export
* Reproducible Pipeline

## Sample Metrics

* Total Products
* Product Categories
* Sale Price
* Regular Price
* Discount Amount
* Discount Percentage

## Skills Demonstrated

* Data Extraction
* ETL Pipeline Development
* API Integration
* Data Cleaning
* Data Transformation
* Data Analysis
* GitHub Project Management
* Data Engineering Fundamentals

## Future Improvements

* Load data into PostgreSQL
* Process data using PySpark
* Automate workflows using Apache Airflow
* Store data in AWS S3
* Create Power BI dashboards
* Implement data quality checks and monitoring

## Author

Rajan Yadav

Aspiring Data Engineer | Python | SQL | PySpark | Airflow | AWS | Data Engineering

This project was created to demonstrate practical Data Engineering skills through the implementation of a real-world e-commerce data pipeline.
