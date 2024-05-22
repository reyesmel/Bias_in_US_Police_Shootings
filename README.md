# Bias_in_US_Police_Shootings

#### Background
DSCI 531: Fairness in Artificial Intelligence<br/>
USC Viterbi School of Engineering Data Science Program<br/>
Final Project

This project investigated the relationship between fatal police shootings and mental illness using logistic regression model on 8,000 shootings to explore potential bias. Evaluated model performance using F1, precision, recall, and accuracy scores.  Found distribution of shootings didn’t correlate by state population (CA, TX, FL) and effect size decreased when analyzing across state/political party.<br/>

The dependent variable in this analysis is the presence of signs of mental illness, as it is the variable of interest being investigated for its relationship with other factors.<br/>

The independent variables are:<br/>

* Victim's race
* State the victim resided in at the time of death
* Political party majority associated with each state

These independent variables are being investigated to determine their influence on the dependent variable, the manifestation of signs of mental illness.<br/>

### General Note:
Code originally ran on google colab.

#### Sources
1. [Washinton Post Fatal Police Shootings Database](https://www.washingtonpost.com/graphics/investigations/police-shootings-database/)

#### Packages Required
* numpy
* pandas
* matplotlib
* sklearn
* seaborn

#### Files Required
* WaPo_Database_Preprocessing_Code.ipynb
* WaPo_Clean_Data_Inital_Exploratory_Analysis.ipynb 
* Creating_WaPo_Binary_Database_Exploratory_Analysis.ipynb
* Logistic_Regression_w_Bootstrapping_Mental_Illness_Code.ipynb
* cleaned_data.csv

#### How to run code:
1. Logistic Regression code runs on the cleaned_data.csv dataset and run analysis on the full cleaned data as well as the binary simplified database.
