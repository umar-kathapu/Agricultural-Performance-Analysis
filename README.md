# Seasonal Agriculture Performance Analysis

## Major Project – VOIS for Tech AICTE Batch 1 2026–2027

This project analyzes agricultural performance across different seasons using data analytics techniques. The analysis focuses on identifying seasonal patterns, relationships, variations, resource usage, and economic performance.

## 📌 Problem Statement

Agricultural performance can vary across seasons due to differences in environmental conditions, farming practices, resource availability, and market conditions.

This project analyzes the given agricultural dataset to identify meaningful seasonal patterns, trends, relationships, and variations in agricultural performance.

## 🎯 Objectives

- Analyze agricultural performance across different seasons.
- Compare crop yield and production across seasons.
- Examine seasonal resource usage.
- Analyze relationships between environmental factors and agricultural outcomes.
- Compare seasonal revenue and profitability.
- Identify unusual patterns and significant observations.
- Develop evidence-based insights and recommendations.

## 📊 Dataset

The dataset contains agricultural information related to:

- Season
- State and District
- Crop
- Irrigation Method
- Rainfall
- Temperature
- Humidity
- Soil Conditions
- Fertilizer Usage
- Pesticide Usage
- Water Usage
- Crop Yield
- Production
- Market Price
- Cost
- Revenue
- Profit

The dataset contains **4,000 records and 28 columns**.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

## 🔍 Analysis Performed

### 1. Data Understanding
- Dataset shape and structure
- Column and data type analysis
- Descriptive statistics

### 2. Data Cleaning
- Missing value identification
- Missing value treatment
- Duplicate checking
- Data validation

### 3. Outlier Analysis
Outliers were identified using the Interquartile Range (IQR) method and investigated before analysis.

### 4. Seasonal Performance Analysis
Agricultural performance was compared across:
- Kharif
- Rabi
- Zaid

Performance indicators included:
- Yield
- Production
- Revenue
- Profit

### 5. Correlation Analysis
Relationships between environmental conditions, resource usage, yield, and profit were examined using correlation analysis.

### 6. Resource Usage Analysis
Seasonal differences in:
- Water usage
- Fertilizer usage
- Pesticide usage

were analyzed.

## 📈 Key Findings

- **Kharif** recorded the highest average yield at approximately **5.63 tonnes/ha**.
- Kharif also recorded the highest average production, revenue, and profit.
- **Zaid** recorded the lowest average yield at approximately **4.64 tonnes/ha**.
- Zaid had the highest average water usage at approximately **6,419.89 m³**.
- Despite higher water usage, Zaid recorded the lowest average yield and a negative average profit.
- Yield showed the strongest positive correlation with profit among the analyzed variables, with a correlation of approximately **0.48**.

## 💡 Recommendations

- Prioritize suitable agricultural activities during high-performing seasons such as Kharif.
- Improve water management and irrigation efficiency during Zaid.
- Review production costs and market conditions during low-profit seasons.
- Optimize fertilizer, pesticide, and water usage according to seasonal requirements.
- Use data-driven seasonal planning to improve productivity and profitability.

## 📁 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── seasonal_agriculture_performance_dataset.csv
└── README.md