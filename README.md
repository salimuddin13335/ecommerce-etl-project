
# E-commerce Sales Data ETL Mini-Project

## Project Overview
This project builds a small ETL pipeline using Python and pandas.
It extracts, cleans, transforms and processes an open e-commerce dataset.

## Dataset
Source: UCI Online Retail Dataset

## ETL Process

### 1. Extract
- Download the original CSV dataset.
- Load the dataset using pandas.

### 2. Transform
- Check missing values.
- Remove duplicate records.
- Remove missing product descriptions.
- Convert InvoiceDate to datetime.
- Retain missing CustomerIDs.
- Identify cancelled transactions.
- Remove cancelled invoices and invalid sales.
- Calculate revenue using Quantity * UnitPrice.

### 3. Load
- Export the processed dataset as a CSV file.

## Tools Used
- Python
- Pandas
- Google Colab
- GitHub

## Results
- Processed sales records: 524878
- Cancelled transactions identified: 9251
- Remaining duplicates: 0
- Sales revenue: £10,642,110.80

## Output
cleaned_ecommerce_sales.csv

## Purpose
The processed CSV can be used for further analysis and dashboard development.
