# Project1_decodelabs
# E-Commerce Data Cleaning and Analysis Project

## 📌 Project Overview

This project focuses on cleaning and analyzing an e-commerce sales dataset using Python.  
The main objective is to preprocess raw customer order data, handle missing values, remove inconsistencies, and prepare the dataset for further data analysis.

The project demonstrates practical Data Analytics workflow using Python libraries like Pandas and NumPy.

---

## 🎯 Objectives

- Load and understand the dataset structure
- Perform data exploration
- Identify missing values and data issues
- Clean and preprocess the dataset
- Remove duplicate records
- Convert data types correctly
- Handle inconsistent text values
- Detect outliers in numerical columns

---

## 🛠️ Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib

---

## 📂 Dataset Description

The dataset contains e-commerce order details including:

- Order ID
- Date
- Customer ID
- Product
- Quantity
- Unit Price
- Shipping Address
- Payment Method
- Order Status
- Tracking Number
- Items in Cart
- Coupon Code
- Referral Source
- Total Price

Dataset contains **1200 records and 14 columns**. :contentReference[oaicite:2]{index=2}

---

## 🔍 Project Workflow

### 1. Import Required Libraries

Imported Python libraries required for data manipulation and analysis.

---

### 2. Data Loading

Loaded the CSV dataset using Pandas:

```python
df = pd.read_csv("Dataset for Data Analytics - Sheet1.csv")

