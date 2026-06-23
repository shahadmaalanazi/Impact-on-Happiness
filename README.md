# Impact on Happiness Analysis

## Overview
This project explores the factors that influence happiness scores using data from the World Happiness Report (2018–2019).

The analysis includes data exploration, visualization, feature correlation analysis, and machine learning models to predict happiness scores based on socioeconomic indicators.

---

## Objectives

- Analyze factors affecting happiness levels.
- Explore relationships between happiness score and key indicators.
- Visualize distributions, correlations, and outliers.
- Build predictive machine learning models.
- Compare model performance and identify the most important factors influencing happiness.

---

## Dataset Features

The dataset includes:

- Happiness Score
- GDP per Capita
- Social Support
- Healthy Life Expectancy
- Freedom to Make Life Choices
- Generosity
- Perceptions of Corruption

---

## Data Analysis

The project performs:

### Data Cleaning
- Removing non-numeric columns
- Checking missing values
- Statistical summary of the dataset

### Exploratory Data Analysis (EDA)
- Histograms for feature distributions
- Happiness score distribution
- Bar plots for important features
- Outlier detection using boxplots
- Correlation heatmap

### Happiness Classification
Countries are categorized into:

- Low Happiness
- Medium Happiness
- High Happiness

based on their happiness score.

---

## Machine Learning Models

### Random Forest Regressor
- Hyperparameter tuning using GridSearchCV
- Performance evaluation using:
  - R² Score
  - RMSE

### ElasticNet Regression
- Fine-tuned using GridSearchCV
- Performance evaluation using:
  - R² Score
  - RMSE
  - MAE

---

## Feature Importance

Random Forest feature importance is used to identify the most influential variables contributing to happiness scores.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

1. Load and inspect data
2. Clean and preprocess dataset
3. Perform exploratory data analysis
4. Create happiness categories
5. Scale numerical features
6. Train machine learning models
7. Optimize models using GridSearchCV
8. Evaluate performance
9. Compare models
10. Analyze feature importance

---

## Results

The project compares Random Forest and ElasticNet models to determine the most effective approach for predicting happiness scores.

Key findings include:
- Economic indicators strongly influence happiness.
- Social support and life expectancy have significant impact.
- Machine learning models can accurately estimate happiness scores from socioeconomic features.

---
