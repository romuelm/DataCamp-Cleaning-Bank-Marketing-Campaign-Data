# 📊 Cleaning Bank Marketing Campaign Data

## 📌 Overview
This project focuses on cleaning and preprocessing a bank marketing dataset to prepare it for analysis and machine learning. The dataset contains client information used in direct marketing campaigns, such as demographics, financial status, and loan details.

The goal is to transform raw, inconsistent data into a structured and usable format.

---

## 🧹 Data Cleaning Steps

### 1. Column Formatting
- Replaced "." with "_" in categorical columns:
  - job
  - education

### 2. Handling Missing Values
- Replaced "unknown" values in the education column with NaN

### 3. Boolean Conversion

Credit Default:
- True → if "yes"
- False → if "no" or "unknown"

Mortgage:
- True → if "yes"
- False → if "no" or "unknown"

---

## 📂 Final Dataset
Selected columns:
- client_id
- age
- job
- marital
- education
- credit_default
- mortgage

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy

---

## 🎯 Objective
To create a clean dataset that can be used for:
- Data analysis
- Machine learning
- Marketing insights

---

## 🚀 Future Improvements
- Encode categorical variables
- Handle outliers
- Feature engineering
- Build predictive models

---

## 📎 Notes
This project is part of a DataCamp exercise on data cleaning.
