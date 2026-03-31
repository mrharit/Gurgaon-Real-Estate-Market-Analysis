# 🏙️ Gurgaon Real Estate Market Analysis
### Exploratory Data Analysis (EDA) Project

---

## 📌 Project Overview

This project performs an **in-depth Exploratory Data Analysis (EDA)** on residential real estate data from **Gurgaon, India**, aimed at generating **data-driven insights for buyers, investors, and real estate developers**.

Gurgaon is one of India’s fastest-growing real estate markets, with significant price variation across localities, builders, property types, and regulatory approvals. This analysis answers critical business questions to support informed decision-making.

---

## 🎯 Problem Statement

You are working as a **Data Analyst for a real estate advisory firm** operating in Gurgaon.  
The firm has collected residential property data across multiple localities and wants to extract meaningful **market insights**.

The objective is to:
- Identify premium localities and properties
- Compare pricing across construction status and approvals
- Understand how size, BHK, and builders affect pricing

---

## 📂 Dataset Information

- **Source:** Kaggle  
- **Dataset:** Gurgaon Real Estate Dataset  
- **Link:**  
  https://www.kaggle.com/datasets/nikhilmehrahr26/gurgaon-real-estate-dataset  

### Key Columns
- `price`
- `area`
- `rate_per_sqft`
- `locality`
- `bhk_count`
- `flat_type`
- `company_name`
- `status`
- `rera_approval`

---

## ❓ Business Questions Answered

1. Which is the **costliest flat** in the dataset?
2. Which locality has the **highest average price**?
3. Which locality has the **highest rate per square foot**?
4. Do **ready-to-move properties** cost more than **under-construction** ones?
5. Do **RERA-approved properties** command a premium?
6. How does **area** impact property price?
7. Which **BHK configuration** is the most expensive?
8. Which **property type** is the costliest?
9. Do certain **builders** consistently price higher?
10. Are **larger homes** always more expensive per square foot?

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 Methodology

### 1. Data Loading
- Imported dataset using Pandas
- Checked shape, column names, and data types

### 2. Data Cleaning
- Standardized column names
- Converted numerical columns
- Cleaned categorical values
- Removed duplicate entries

---

## 📊 Exploratory Data Analysis (EDA)

The analysis was carried out using:
- Grouped aggregations (`groupby`)
- Median-based comparisons
- Scatter plots for relationship analysis
- Price comparisons across categories

Key visualizations include:
- Area vs Price
- Area vs Rate per Sqft

---

## ✅ Key Insights

- Premium localities command **higher prices and rate per sqft**
- **Ready-to-move properties** are generally more expensive
- **RERA-approved properties** attract a trust premium
- **Builder reputation** significantly impacts pricing
- Larger homes are **not always more expensive per sqft**
- Apartments usually have a **higher rate per sqft** than floors and plots

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/gurgaon-real-estate-analysis.git
