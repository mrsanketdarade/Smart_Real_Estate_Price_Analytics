# 🏠 Smart Real Estate Price Analytics

**End-to-End Data Analytics Project Using Python**

## 📌 Project Overview

Smart Real Estate Price Analytics is a data analytics project that analyzes housing data to understand the main factors affecting house prices. This project follows the complete data analytics process, including data cleaning, handling missing values, Exploratory Data Analysis (EDA), data visualization, and generating business insights using Python.

The dataset contains missing values and outliers, making it useful for practicing real-world data analytics skills.

## 🎯 Project Objectives

- Clean and prepare raw housing data.
- Handle missing values using suitable statistical methods.
- Perform Exploratory Data Analysis (EDA).
- Create visualizations using Matplotlib and Seaborn.
- Identify the main factors affecting property prices.
- Generate useful insights for real estate buyers, sellers, and investors.

## 🛠️ Skills and Tools Used

- Python
- NumPy and Pandas
- Data Cleaning and Preprocessing
- Missing Value Treatment
- Exploratory Data Analysis (EDA)
- Data Visualization
- Matplotlib and Seaborn
- Business Analytics

## 📂 Dataset Information

**Dataset:** King County House Sales Dataset

- **Rows:** 21,613
- **Columns:** 22
- **Target Variable:** `price`

**Important Features:**
- Property size: `sqft_living`, `sqft_lot`
- Structure: `bedrooms`, `bathrooms`, `floors`
- Quality: `grade`, `condition`
- Location: `zipcode`, `waterfront`, `view`
- Construction: `yr_built`, `yr_renovated`

## 🔍 Project Workflow

### 1. Data Loading and Understanding
Loaded the dataset using Pandas and checked its size, data types, summary statistics, and missing values.

### 2. Data Cleaning and Preprocessing
Removed the unnecessary index column, converted the date column into the correct datetime format, and checked the data for inconsistencies.

### 3. Missing Value Treatment
Missing values were identified in the `bedrooms` and `bathrooms` columns. Median imputation was used to fill these missing values while reducing the influence of outliers.

### 4. Exploratory Data Analysis (EDA)
Created histograms, scatter plots, box plots, and correlation heatmaps to study price distribution and understand the relationships between property features and house prices.

### 5. Feature Engineering
Created three new features:
- `house_age`: Calculates the age of the property.
- `is_renovated`: Identifies whether a property has been renovated.
- `price_per_sqft`: Calculates the price per square foot for property comparison.

### 6. Segment-Wise Analysis
Grouped properties into budget, mid-range, and luxury segments to compare pricing patterns across different market categories.

### 7. Data Visualization
Created visualizations using Matplotlib and Seaborn to present the findings in a clear and understandable way.

## 📊 Key Insights

1. Living area is an important factor affecting house prices.
2. Construction grade has a significant relationship with property prices.
3. Bathrooms may provide more pricing insight than bedroom count.
4. Renovated and waterfront properties can belong to premium market segments.
5. Lot size alone may not fully explain property prices.

## 📈 Business Recommendations

1. Consider living area and construction quality when evaluating properties.
2. Evaluate renovation costs against potential increases in property value.
3. Highlight waterfront access and attractive views when marketing premium properties.
4. Compare properties using price per square foot and location.

## ⚠️ Limitations and Assumptions

**Limitations:**
- Property prices have not been adjusted for inflation.
- Location analysis is limited to ZIP code information.
- The project focuses on data analysis and does not include a predictive model.

**Assumptions:**
- The dataset reasonably represents the housing market during the recorded period.
- The analysis does not account for major economic changes over time.

## ✅ Conclusion

This project helped me develop practical skills in Python, data cleaning, data preprocessing, exploratory data analysis, and data visualization. It also helped me understand how property features influence housing prices and how data-driven insights can support better real estate decisions.
