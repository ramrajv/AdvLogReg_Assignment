# AdvLogReg_Assignment
Assignment for advanced logistics regression from Upgrad Oct 21 EPGP program

# Introduction
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. The python notebook attached details the regression model using regularisation to predict actual value.

# Aim
To predict actual value of prospective properties.

# Required Information
List of significant variables and how well they describe house price.

# Process used in the notebook

## Exploratory Data Analytics
1. The target variale is the sale price of houses. The data given in the dataset was cleaned and checked for effect on the sale price. Business metrics were derived using available features.
2. Skew in variables were removed using log and square root functions.
3. Certain objective variables with high skewness were removed.

## Regression
1. RFE was used to get 30 most significant variables.
2. Linear, Ridge and Lasso regressions were used on dataset.
3. Measures of regression were detailed.

# Results
1. Lasso regressor provided slightly better results compared to ridge and linear.
2. There was no significant differences between performance of all three regressors.

# Significant features
The significant features for lasso regression are: -

  Positively influencing factors: -

    Lot area (log value).
    First floor square feet area (log value).
   Negatively Influencing factors: -

    Price per square feet (log value).
    Ground Living area (log value).
    Bedroom above ground (original value).

The significant features from Ridge and linear Regressions are: -

  Positively influencing factors: -

    Lot area (log value).
    Lot frontage (log value).
    
  Negatively influencing factors: -

    Length Width Ratio (log value).
    Price per square feet (log value).
    Ground living area (log value).
