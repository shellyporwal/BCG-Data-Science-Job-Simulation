
# BCG Data Science Job Simulation – Customer Churn Prediction

## Project Overview

This project was completed as part of the BCG Data Science Job Simulation. The objective was to analyze customer and pricing data for PowerCo, identify the key drivers of customer churn, and develop a predictive machine learning model to support retention strategies.

The project combines exploratory data analysis, feature engineering, machine learning, and business recommendations to help reduce customer attrition and improve customer lifetime value.

---

## Business Problem

PowerCo observed increasing customer churn and wanted to understand:

- Which customers are most likely to churn?
- What factors drive customer churn?
- How can the business proactively retain customers?
- Is price sensitivity a major contributor to churn?

---

## Project Objectives

- Clean and prepare customer and pricing datasets.
- Perform exploratory data analysis (EDA).
- Identify churn patterns and customer behaviors.
- Engineer meaningful predictive features.
- Build a churn prediction model.
- Interpret model outputs.
- Generate actionable business recommendations.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn


---

## Project Workflow

### 1. Data Cleaning

- Checked and handled missing values
- Converted data types
- Removed duplicates
- Validated data quality

### 2. Exploratory Data Analysis

Analyzed:

- Customer churn distribution
- Customer tenure
- Product modification behavior
- Energy consumption patterns
- Pricing characteristics
- Margin-related metrics

### 3. Feature Engineering

Created additional features including:

- Customer tenure
- Off-peak price differences
- Consumption trends
- Margin-related metrics
- Contract duration indicators

### 4. Machine Learning

A Random Forest Classifier was used to predict customer churn.

Model evaluation included:

- Accuracy
- Precision
- Recall
- Feature Importance
- Permutation Importance

---

## Key Business Insights

### Customer Tenure

Customers with less than 5 years of tenure were significantly more likely to churn.

### Product Modification Behavior

Customers who modified their products within the first 4 years of activation showed a higher probability of churn.

### Customer Composition

Only 18.15% of customers were identified as gas clients.

### Profitability Metrics

Net margin and power subscription margin emerged as strong predictors of churn.

### Consumption Patterns

Consumption over the previous 12 months was among the most influential features in predicting customer churn.

### Pricing Factors

Although some price sensitivity variables appeared important in feature importance rankings, permutation importance analysis suggested that price sensitivity is not a primary driver of churn.

---

## Model Findings

The model identified the following as the most influential churn drivers:

1. Net Margin
2. Consumption over 12 Months
3. Power Subscription Margin
4. Customer Tenure
5. Contract Duration
6. Off-Peak Energy Price Changes

### Key Observation

Customer churn appears to be driven more by customer lifecycle, profitability, and consumption behavior than by pricing alone.

---

## Strategic Recommendations

### 1. Target Newer Customers with Early Retention Programs

Customers with less than 5 years of tenure are more likely to churn.

**Recommendation:**

Implement targeted retention and engagement programs during the first 3–5 years of the customer lifecycle.

---

### 2. Create Churn Risk Alerts for Product Modification Events

Customers modifying products within the first 4 years after activation exhibit higher churn tendencies.

**Recommendation:**

Treat product modification requests as potential churn signals and proactively engage these customers.

---


### 3. Investigate Off-Peak Energy Price Change Effects

Changes in off-peak energy pricing were found to influence churn predictions.

**Recommendation:**

Review pricing communication strategies and evaluate customer responses to tariff changes.

---

## Business Impact

The developed churn prediction framework enables PowerCo to:

- Identify high-risk customers proactively
- Improve customer retention strategies
- Optimize retention spending
- Protect revenue from high-value customers
- Support data-driven decision-making

---



This project demonstrates how exploratory data analysis, feature engineering, and machine learning can be applied to understand customer churn and generate actionable business recommendations. The findings suggest that customer tenure, profitability metrics, and consumption behavior play a more significant role in churn than price sensitivity, providing valuable insights for PowerCo's customer retention strategy.
