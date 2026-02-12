# 📊 Level 1 – Task 1: Data Cleaning and Preprocessing

## 🏢 Internship
Data Analysis Internship – Codveda Technologies

---

## 📌 Project Overview

This project focuses on cleaning and preprocessing a raw dataset as part of Level 1 – Task 1 of the internship.

The dataset belongs to the Customer Churn Analysis domain.  
The objective was to transform raw data into a clean and structured format suitable for further analysis and modeling.

---

## 📂 Dataset Information

- Dataset Name: churn-bigml-80.csv
- Domain: Customer Churn Analysis
- Total Rows: 2666
- Total Columns: 20

The dataset contains customer account details, usage statistics, service information, and churn status.

---

## 🛠 Tools & Technologies Used

- Programming Language: Python
- Library: Pandas
- Environment: Google Colab / VS Code
- Version Control: Git & GitHub

---

## 🔍 Project Workflow

### 1. Load Dataset
- Imported Pandas
- Loaded dataset using read_csv()
- Displayed initial rows using head()

### 2. Understand Dataset Structure
- Checked dataset shape
- Used info() to analyze data types
- Verified number of rows and columns

### 3. Handle Missing Values
- Used isnull().sum() to detect missing values
- Confirmed no significant missing values

### 4. Remove Duplicate Records
- Checked duplicates using duplicated().sum()
- Removed duplicates using drop_duplicates()

### 5. Standardize Categorical Data
- Converted text columns to lowercase
- Removed extra spaces using str.strip()
- Ensured consistency across categorical variables

### 6. Convert Boolean Columns
- Converted boolean columns into numerical format (0 and 1)
- Prepared dataset for machine learning compatibility

### 7. Export Cleaned Dataset
- Saved cleaned dataset as cleaned_dataset.csv

---

## ✅ Final Outcome

After preprocessing:

- No missing values
- No duplicate records
- Standardized categorical data
- Boolean columns converted to numeric format
- Dataset ready for Exploratory Data Analysis and Predictive Modeling

---

## 🚀 Learning Outcomes

- Real-world data cleaning experience
- Handling structured datasets using Pandas
- Managing categorical and boolean data types
- Understanding the importance of preprocessing before analysis

---

## 📁 Project Files

data/
    churn-bigml-80.csv

notebook/
    data_cleaning_preprocessing.ipynb

output/
    cleaned_dataset.csv

README.md

---

## 👤 Author

Sai Santosh Mukadam  
Data Analysis Intern – Codveda Technologies  

GitHub: https://github.com/saimukadam  
LinkedIn: https://www.linkedin.com/in/sai-mukadam-54a416267/

---

⭐ If you found this project useful, feel free to connect and collaborate.

