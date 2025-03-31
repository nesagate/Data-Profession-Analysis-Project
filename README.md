# 📊 Data Analyst Salary Data Cleaning & Analysis

## 📚 Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Dataset Details](#dataset-details)
- [Repository Structure](#repository-structure)
- [Tools Used](#tools-used)
- [How to Use This Repository](#how-to-use-this-repository)
- [Results](#results)
- [Future Work](#future-work)
- [Contributors](#contributors)

---

## 📌 Overview
This project focuses on cleaning and analyzing a dataset containing salary information for data analysts. The dataset includes job titles, industries, salary ranges, and other relevant details. The goal is to clean, structure, and analyze the data using Microsoft Excel.

---

## 🚨 Problem Statement
The dataset had several issues, including:
- **Missing values** in key columns
- **Inconsistent job titles** (e.g., different variations of "Data Analyst")
- **Industry misclassification** (e.g., "Other" category being too broad)
- **Salary range formatting** (e.g., "106k-125k" needed to be converted into numerical values)

These issues made it difficult to extract meaningful insights about salary trends across different industries and job titles.

---

## 🎯 Objectives
### 1️⃣ Data Cleaning
- Remove duplicate entries
- Standardize job titles and industry categories
- Convert salary ranges into numerical values and compute average salary

### 2️⃣ Data Analysis
- Identify the **top-paying industries**
- Analyze the **most common job titles**
- Examine salary trends across industries

### 3️⃣ Dashboard Creation
- Visualize key insights using **Excel Dashboards**

---

## 📊 Dataset Details
| Column Name          | Description |
|----------------------|-------------|
| Job Title           | Title of the data-related job |
| Industry            | Industry the job falls under |
| Salary Range        | Salary range in text format (e.g., "41k-65k") |
| Average Salary (USD) | Converted numerical average of salary range |

---

## 📁 Repository Structure
```
Salary-Data-Analysis/
│── data/
│   ├── raw_data.xlsx      # Original dataset
│   ├── cleaned_data.xlsx  # Cleaned dataset
│
│── documentation/
│   ├── data_cleaning_steps.docx  # Step-by-step cleaning process
│
│── visuals/
│   ├── dashboard.png  # Screenshot of the final dashboard
│
│── README.md  # Project documentation
```

---

## 🛠️ Tools Used
- **Microsoft Excel** – Data cleaning, analysis, and visualization
- **GitHub** – Version control and documentation

---

## 📖 How to Use This Repository
1. **Download or Clone** the repository:
   ```bash
   git clone https://github.com/yourusername/salary-data-analysis.git
   ```
2. Open the `data/` folder to access the raw and cleaned datasets.
3. Check the `documentation/` folder for detailed data cleaning steps.
4. Open `visuals/dashboard.png` to see the final dashboard.

---

## 📊 Results
- The **top-paying industry** was `XYZ Industry` with an average salary of `$XYZk`.
- **Most common job title** was `Data Analyst`, making up `XX%` of all roles.
- The **"Other" industry issue** was resolved by reclassifying jobs correctly.

---

## 🚀 Future Work
- Expand dataset with more job postings for a **larger sample size**.
- Perform advanced **statistical analysis** using SQL or Python.
- Create an **interactive Power BI dashboard** for deeper insights.

---

## 💡 Contributors
- **Vanesa Gate** – Data Analyst

---

![Dashboard Preview](visuals/dashboard.png)
