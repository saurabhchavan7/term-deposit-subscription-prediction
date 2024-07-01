## Business Problem

### Problem Statement:
The bank aims to enhance revenue by increasing subscriptions to long-term deposits among its clients through targeted telemarketing. The objective is to predict which clients are more likely to subscribe, optimizing marketing efforts to improve conversion rates and overall customer satisfaction.

### Project Background:
In the competitive banking industry, effective marketing strategies are crucial for maximizing returns on marketing investments. By analyzing customer demographics and relevant banking data, the bank aims to predict customer behaviors related to savings and identify potential term deposit subscribers. This predictive capability will enable targeted marketing campaigns that efficiently secure deposits while enhancing customer satisfaction by minimizing irrelevant advertisements.

## Dataset

- **Dataset Link**: [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Description**: The dataset contains information related to direct marketing campaigns of a Portuguese banking institution, including features such as client demographics, economic indicators, and campaign outcome (target variable).

## Table of Contents

1. **Data Exploration**
   - Importing Libraries
   - Loading Dataset
   - Feature Description
   - Summary of Features

2. **Preparing the Dataset for Machine Learning**
   - Defining the Target Variable (Y) and Independent Variables (X)
   - Splitting Data into Numerical and Categorical Features
   - Handling Missing Values
   - Outlier Analysis of Numerical Features
     - Capping and Flooring of Outliers
   - Feature Selection
     - Numerical Features
       - Removing Features with Zero Variance
       - Bi-Variate Analysis (Feature Discretization)
       - Insights
     - Categorical Features
       - Bivariate Analysis
       - Insights

3. **Encoding Categorical Variables**
   - Encoding Categorical Variables into Dummy Variables for Machine Learning

4. **Train-Test Split**

5. **Model Building**
   - **Logistic Regression**
     - Understanding Logistic Regression Coefficients
     - Insights from Logistic Regression Analysis
   - **Decision Tree**
   - **Random Forest**
   - **Gradient Boosting**
   - **Stacking Classifier**

6. **Model Evaluation**
   - Performance Metrics (Accuracy, Precision, Recall, F1-score)
   - Confusion Matrix Analysis

7. **Marketing Campaign Effectiveness: Insights Report**
   - Gains Chart Analysis
   - Conclusion and Next Steps

8. **Practical Recommendations**
   - Step 1: Create Target Zones
   - Step 2: Slice the Data Based on Top Predicted Customers from the GBM Model Output
   - Step 3: Prioritize by Call Duration


### Step 1: Clone the repository

```sh
git clone https://github.com/your-username/bank-marketing-campaign.git
```

### Step 2:  Navigate to the project directory

```sh
cd bank-marketing-campaign
```

### Step 3: Install the required dependencies

```sh
pip install -r requirements.txt
```