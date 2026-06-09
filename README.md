# Sales-Prediction-Advertising-Channel-Analysis
# Sales Prediction Using Python

## Project Overview

This project focuses on predicting future sales using machine learning techniques in Python. The objective is to analyze the relationship between advertising expenditure and sales performance, then build predictive models that can estimate future sales outcomes. By leveraging historical marketing and sales data, businesses can make informed decisions about budget allocation, campaign planning, and overall marketing strategy.

The project covers the complete data science workflow, including data collection, data cleaning, exploratory data analysis (EDA), feature engineering, model development, evaluation, and sales forecasting. Various regression techniques are used to identify the impact of advertising channels on sales and generate accurate predictions.

---

##  Objectives

- Analyze advertising and sales datasets.
- Clean and preprocess raw data.
- Perform exploratory data analysis to discover trends and patterns.
- Identify relationships between advertising spend and sales.
- Build machine learning models for sales prediction.
- Evaluate model performance using regression metrics.
- Forecast future sales based on advertising budgets.
- Provide actionable business recommendations.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Project Structure

Sales-Prediction-Project/

├── data/

│ └── Advertising.csv

├── notebooks/

│ └── Sales_Prediction.ipynb

├── images/

│ ├── correlation_heatmap.png

│ ├── sales_distribution.png

│ ├── advertising_vs_sales.png

│ └── actual_vs_predicted.png

├── reports/

│ └── Project_Report.pdf

├── README.md

└── requirements.txt

---

##  Dataset Description

The dataset contains advertising expenditure across multiple marketing channels and corresponding sales figures.

### Features

| Feature | Description |
|----------|-------------|
| TV | Advertising budget spent on TV |
| Radio | Advertising budget spent on Radio |
| Newspaper | Advertising budget spent on Newspapers |
| Sales | Product sales generated |

### Target Variable

**Sales**

The target variable represents the sales generated based on advertising investments.

---

##  Methodology

### 1. Data Collection

- Load the advertising dataset.
- Examine the structure and contents of the dataset.

### 2. Data Cleaning

- Handle missing values.
- Remove duplicate records.
- Verify data types.
- Prepare data for analysis.

### 3. Exploratory Data Analysis (EDA)

- Analyze feature distributions.
- Generate descriptive statistics.
- Create visualizations to understand relationships.
- Identify trends and patterns.

### 4. Feature Selection

- Select advertising-related features.
- Define the target variable.
- Prepare input variables for machine learning models.

### 5. Model Development

The following regression algorithms can be implemented:

#### Linear Regression

A statistical method used to model the relationship between advertising expenditure and sales.

#### Decision Tree Regressor

A tree-based model capable of capturing non-linear relationships.

#### Random Forest Regressor

An ensemble learning algorithm that improves prediction accuracy and reduces overfitting.

### 6. Model Evaluation

Evaluate model performance using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 7. Sales Forecasting

Generate future sales predictions using new advertising budget values.

---

## Visualizations

The project includes several visualizations to better understand the data:

- Correlation Heatmap
- Sales Distribution Plot
- TV Advertising vs Sales
- Radio Advertising vs Sales
- Newspaper Advertising vs Sales
- Actual vs Predicted Sales Comparison
- Feature Importance Analysis

---

##  Machine Learning Models

### Linear Regression

Used as the baseline predictive model for sales forecasting.

### Decision Tree Regressor

Captures complex relationships between advertising expenditure and sales outcomes.

### Random Forest Regressor

Combines multiple decision trees to improve predictive performance.

---

## Evaluation Metrics

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures the standard deviation of prediction errors.

### R² Score

Represents the proportion of variance in sales explained by the model.

| R² Score | Interpretation |
|-----------|---------------|
| 0.90 – 1.00 | Excellent |
| 0.80 – 0.89 | Very Good |
| 0.70 – 0.79 | Good |
| Below 0.70 | Needs Improvement |

---

##  Key Insights

- Advertising expenditure significantly influences sales performance.
- TV advertising often has the strongest impact on sales.
- Radio advertising contributes positively to revenue growth.
- Newspaper advertising generally has a weaker effect on sales.
- Machine learning models can effectively forecast future sales outcomes.

---

##  Business Recommendations

Based on the analysis, organizations can:

- Increase investment in high-performing advertising channels.
- Optimize marketing budgets using predictive insights.
- Improve campaign planning through sales forecasting.
- Enhance return on investment (ROI) through data-driven decision-making.
- Use predictive analytics to support long-term business growth.

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/your-username/sales-prediction-project.git
```

Navigate to the project directory:

```bash
cd sales-prediction-project
```

Install required packages:

```bash
pip install -r requirements.txt
```

---

##  Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Sales_Prediction.ipynb
```

Run all cells to:

- Explore the dataset
- Train machine learning models
- Evaluate model performance
- Generate sales predictions
- Visualize results

---

##  Requirements

Create a `requirements.txt` file containing:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

##  Learning Outcomes

By completing this project, you will gain practical experience in:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Regression Analysis
- Machine Learning Model Development
- Model Evaluation
- Sales Forecasting
- Business Intelligence

---

## Internship Project

This project was completed as part of a Data Science Internship Program focused on practical applications of machine learning, predictive analytics, and business decision support systems.

The project demonstrates how data science techniques can be used to transform advertising data into valuable business insights and accurate sales predictions.

---

##  Author

**Your Name**

Data Science Intern

GitHub: https://github.com/your-username

LinkedIn:www.linkedin.com/in/peter-okomesi-30b98234

---
