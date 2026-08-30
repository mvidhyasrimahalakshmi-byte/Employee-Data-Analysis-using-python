# HR Analytics & Employee Attrition Analysis

## 📌 Project Overview

This project analyzes employee HR data to understand employee attrition and identify patterns related to department, job role, salary, job satisfaction, age, performance, and experience.

The project demonstrates an end-to-end Python Data Analyst workflow, including data analysis, visualization, statistical testing, and business insight generation.

---

## 🎯 Business Problem

Employee attrition can affect productivity, recruitment costs, and organizational performance.

This project aims to answer:

- What is the overall employee attrition rate?
- Which departments have higher attrition?
- Which job roles have higher attrition?
- Is monthly income different between employees who stayed and left?
- Is job satisfaction associated with attrition?
- How do age and experience differ between employees who stayed and left?
- Are selected relationships statistically significant?

---

## 📊 Dataset

The project uses a cleaned HR employee dataset.

The dataset contains employee-related information such as:

- Employee demographics
- Department
- Job role
- Monthly income
- Job satisfaction
- Performance rating
- Age
- Years at company
- Attrition

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## 📁 Project Structure

```text
HR_Analytics_Project/
│
├── data/
│   └── HR_analytics(2).csv
│
├── src/
│   └── hr_analysis.py
│
├── charts/
│   ├── 01_employee_attrition.png
│   ├── 02_attrition_by_department.png
│   ├── 03_attrition_by_job_role.png
│   ├── 04_salary_vs_attrition.png
│   ├── 05_job_satisfaction_vs_attrition.png
│   ├── 06_age_vs_attrition.png
│   ├── 07_monthly_income_distribution.png
│   └── 08_correlation_heatmap.png
│
├── reports/
│   └── HR_Analytics_Report.pdf
│
├── README.md
│
└── requirements.txt
```

---

## 🔍 Analysis Performed

### 1. Data Understanding
- Dataset shape
- Column names
- Data types
- Descriptive statistics
- Missing-value checks

### 2. Attrition Analysis
- Overall attrition
- Employees who stayed
- Employees who left
- Attrition rate

### 3. Department Analysis
- Employee distribution by department
- Attrition rate by department

### 4. Job Role Analysis
- Employee distribution by job role
- Attrition rate by job role

### 5. Salary Analysis
- Average monthly income
- Salary distribution
- Monthly income comparison between attrition groups

### 6. Job Satisfaction Analysis
- Job satisfaction distribution
- Job satisfaction comparison between employees who stayed and left

### 7. Age & Experience Analysis
- Age distribution
- Age comparison by attrition
- Years at company comparison

### 8. Correlation Analysis
A correlation matrix and heatmap were created to investigate relationships between numerical variables.

### 9. Statistical Analysis
SciPy was used for:
- Welch's independent t-test
- Chi-square test

---

## 📈 Visualizations

The project contains these important charts:

1. Employee Attrition
2. Attrition Rate by Department
3. Attrition Rate by Job Role
4. Monthly Income vs Attrition
5. Job Satisfaction vs Attrition
6. Age vs Attrition
7. Monthly Income Distribution
8. HR Dataset Correlation Heatmap

---

## 🔬 Statistical Testing

### Monthly Income

A Welch independent two-sample t-test was used to compare monthly income between employees who stayed and employees who left.

### Job Satisfaction

A Welch independent two-sample t-test was used to compare job satisfaction between the two attrition groups.

### Department and Attrition

A Chi-square test was used to examine whether department and attrition are statistically associated.

The significance level used was:

```text
α = 0.05
```

---

## 💡 Key Findings

The analysis identifies differences in employee characteristics between employees who stayed and employees who left.

The main areas investigated were:

- Department-level attrition
- Job-role attrition
- Monthly income
- Job satisfaction
- Employee age
- Years at company

The detailed numerical findings are available in the project report.

---

## 💼 Business Recommendations

- Investigate departments with higher attrition.
- Review retention factors for high-attrition job roles.
- Examine compensation patterns among employees with higher attrition.
- Monitor employee job satisfaction.
- Pay attention to early-tenure employees.
- Use statistical evidence together with additional HR information before making business decisions.

---

## 📄 Project Report

The complete analysis and visualizations are available in:

```text
reports/HR_Analytics_Report.pdf
```

---

## 🚀 How to Run the Project

### Step 1: Open the project in VS Code

Open the `HR_Analytics_Project` folder.

### Step 2: Install the required libraries

```bash
pip install -r requirements.txt
```

### Step 3: Run the Python analysis

From the project root:

```bash
python src/hr_analysis.py
```

### Step 4: View the results

The generated charts are stored in:

```text
charts/
```

---

## 👩‍💻 Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Exploratory Data Analysis
- Data Manipulation
- Statistical Analysis
- Data Visualization
- Business Insight Generation
- Python for Data Analytics

---

## 👤 Author

**Vidhya Sri Mahalakshmi**

Python Data Analyst Project
