# Predicting Life Expectancy Across Countries: 

## Project Overview

This project focuses on **analyzing and predicting life expectancy** based on critical health, economic, and social factors for 193 countries. By leveraging machine learning and statistical methods, the aim is to identify key contributors to life expectancy and provide insights that could guide public health policies and interventions globally.

---

## Dataset Description

The dataset is derived from the *Global Health Observatory (GHO)* under the **World Health Organization (WHO)**, with additional economic data collected from the **United Nations**. It includes information from **2000 to 2015**, reflecting the developments in health and economic sectors that have significantly improved human mortality rates, particularly in developing nations.

### Key Details:
- **Source**: WHO and UN databases.
- **Timeframe**: 2000–2015.
- **Coverage**: 193 countries.
- **Structure**: 
  - **Rows**: 2,938.
  - **Columns**: 22 (20 predictive features + target variable).
  - Categories: **Immunization, Mortality, Economic, and Social factors**.

---

## Workflow

### 1. Exploratory Data Analysis (EDA)

- Used statistical and visual tools to understand relationships between predictors and life expectancy.
- Key insights into disparities between developed and developing countries.

### 2. Data Preprocessing

- **Handling Missing Values**: Missing data for population, Hepatitis B, and GDP were addressed using imputation techniques. Countries with extensive missing data (e.g., Vanuatu, Tonga) were excluded.


### 3. Model Training and Evaluation

The following models were tested:
- **Linear Regression**: For baseline performance.
- **Random Forest**: To capture non-linear interactions.
- **Support Vector Machines (SVM)**: For high-dimensional data.
  
**Evaluation Metrics**:
- R-squared (R²) for model fit.

---

## Results
Full report can be found on *"eda, data cleaning and modeling.ipynb"*
- **Random Forest** performed the best with an **R² of 96.5%** 
- The most significant predictors included:
  - **Income Composition of Resources**.
  - **Status**.
  - **Adult Mortality** levels.

