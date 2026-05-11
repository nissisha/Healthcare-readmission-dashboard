# Healthcare Readmission Executive Dashboard

## Project Overview

This project analyzes healthcare readmission trends using Electronic Health Record (EHR) data and visualizes key insights through an interactive Power BI dashboard.

The dashboard helps identify high-risk patients, readmission patterns, encounter distribution, and clinical insights that can support healthcare decision-making.

---

## Objectives

- Analyze patient readmission trends
- Identify high-risk patient categories
- Monitor average length of stay
- Visualize encounter class distribution
- Explore relationships between age, risk score, and patient conditions

---

## Tools & Technologies

- Power BI
- Python
- Pandas
- CSV Data Processing
- Healthcare EHR Dataset

---

## Dashboard Pages

### 1. Executive Dashboard
Provides KPI-level overview including:
- Total Patients
- Total Encounters
- Readmission Rate
- Average Length of Stay
- High Risk Patients

Includes interactive gender filter slicer.

---

### 2. Patient Risk Analysis
Scatter plot analysis of:
- Age vs Risk Score
- Risk category segmentation
- Patient condition analysis

---

### 3. Clinical Insights
Visualizations showing:
- Encounter class distribution
- Risk category breakdown
- Clinical trend analysis

---

### 4. Length of Stay Distribution
Histogram visualization showing:
- Patient stay duration patterns
- Distribution of hospitalization periods

---

## Repository Structure

```text
Healthcare-readmission-dashboard/
│
├── README.md
├── Healthcare_Readmission_Dashboard.pbix
│
├── processed/
│   ├── ehr_ml_predictions.csv
│   ├── ehr_analytics_dataset.csv
│   └── other processed csv files
│
└── screenshots/

Key Insights:
Higher risk scores are concentrated among specific patient groups
Readmission rate is significantly high across encounters
Length of stay distribution is heavily skewed toward shorter stays
Clinical encounter classes show imbalance across patient categories
Future Improvements:
Add predictive ML models for readmission forecasting
Deploy dashboard to Power BI Service
Add real-time healthcare streaming data
Implement advanced patient segmentation
