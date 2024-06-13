# AeroFit Treadmill Customer Analysis

## Introduction

This repository contains the analysis of AeroFit treadmill customers to identify the characteristics of the target audience for each type of treadmill offered by the company. The analysis aims to provide better recommendations of treadmills to new customers by investigating differences across products with respect to customer characteristics.

## Dataset

The dataset `Aerofit_treadmill.csv` includes information on individuals who purchased a treadmill from AeroFit stores during the prior three months. The dataset features:

- **Product Purchased**: KP281, KP481, or KP781
- **Age**: In years
- **Gender**: Male/Female
- **Education**: In years
- **Marital Status**: Single or Partnered
- **Usage**: The average number of times the customer plans to use the treadmill each week.
- **Income**: Annual income (in $)
- **Fitness**: Self-rated fitness on a 1-to-5 scale, where 1 is poor shape and 5 is excellent shape.
- **Miles**: The average number of miles the customer expects to walk/run each week.

## Analysis

The analysis involves the following steps:

1. **Data Exploration and Cleaning**:
   - Checking the structure and characteristics of the dataset.
   - Detecting and handling outliers.

2. **Descriptive Analytics**:
   - Creating customer profiles for each treadmill product.
   - Constructing two-way contingency tables and computing conditional and marginal probabilities.

3. **Visual Analysis**:
   - Univariate and bivariate analysis using histograms, boxplots, countplots, and heatmaps.
   - Analyzing correlations between different factors.

4. **Insights and Recommendations**:
   - Deriving actionable business insights.
   - Identifying target customer profiles for each treadmill product.
   - Providing recommendations to enhance marketing strategies and product offerings.

## Key Findings

- **Product Distribution**: KP281 is the most popular model, followed by KP481 and KP781.
- **Gender Preferences**: KP781 is predominantly purchased by male customers, while KP281 and KP481 have a more balanced gender distribution.
- **Marital Status**: Partnered individuals are more likely to purchase any of the treadmills compared to single individuals.
- **Correlation Analysis**: Significant correlations were found between fitness level and usage, income, and miles.

## Recommendations

- **KP281**: Target marketing towards young families and new fitness enthusiasts, emphasizing affordability and value.
- **KP481**: Highlight balanced features and durability, targeting regular users looking for a mid-range option.
- **KP781**: Emphasize advanced features and high performance, targeting male customers and serious fitness enthusiasts.
