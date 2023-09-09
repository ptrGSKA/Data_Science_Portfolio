# Data Science Portfolio

This repository containts portfolio of data science projects performed by me in various topics and domains.
They were created for self learning and academic purposes and published in R markdown on RPubs and in Jupyter notebooks.

Data was accessed on Kaggle and used under the specific Licence agreements.

## Instruction to use R and Python analysis

R projects can be viewed locally:
1. Dowload the latest RToold package from CRAN website (https://www.r-project.org/)
2. Install RStudio from https://posit.co/downloads/

Alternatively it can be accessed on RPubs by clicking the links below.

Python projects can be accessed here on Github or alternatively on nbviewer.org (link at the bottom).

## Contents

### Python

- __Exploratory data analysis and data visualization__

  - [Agro-food_CO2_emission](https://github.com/ptrGSKA/Agro-food_CO2_emission): CO2 emission analysis of the agricultural sector. The dataset consists of 30 years of observations worldwide.
            The project started with a short EDA followed by data cleaning. The detailed visualizations provide insights into the emissions from different sectors and countries.
            The analysis finised with hypothesis testing and predictions.
    
    [External link to Agro-food CO2 emission](https://nbviewer.org/github/ptrGSKA/Agro-food_CO2_emission/blob/main/agri-food_co2_emission.ipynb)

  - [Yulu Business Hypothesis testing](https://github.com/ptrGSKA/Business_case-Yulu-Hypothesis_testing):  Analysis of a bike sharing company's data in India. Project started with EDA that followed by feature enginering to better fit for our purpose.
            Data has been downsized and cleaned. This followed by visualization and finised with building ARIMA models to try forecasting the demand. Also revaled in the last section what features are effecting demand most.
    
    [External link to Yulu Business Analysis](https://nbviewer.org/github/ptrGSKA/Business_case-Yulu-Hypothesis_testing/blob/main/Yulu_Business_Hypothesis_Testing.ipynb)

- __Machine Learning__

  - [ Credit_Score_Classification](https://github.com/ptrGSKA/Credit_Score_Classification): The project begins with an EDA phase, followed by data cleaning including removing unnecessary data, adressing inconsistencies and imputing data.
            Data transformation techniques were selected and performed based on the data for preparation for modelling. This followed the machine learning modelling of the data, where the best scoring model achieved over 85% accuracy.
    
    [External link to Credit Score Classification](https://nbviewer.org/github/ptrGSKA/Credit_Score_Classification/blob/main/credit_score_classification.ipynb)

### R

-  __Exploratory data analysis, data visualization and hypothesis testing__

    - [Memory Test Drug Trial Analysis](https://rpubs.com/ptrGSKA/memory_drug_test): Clinical trial of a drug on novel Islanders whom mimic real-life humans in response to external factors. The analysis contains EDA, visualization and hypothesis testing.

- __Machine Learning__
  
  - [Financial Analysis of Global Markets](https://rpubs.com/ptrGSKA/1051903): Market analysis accross global markets in the USA, Europe, London, Hong-Kong and Japan. The time series analysis was carried out in R and an accompanying app was developed in R Shiny.
            This analysis was done as the final graduating project. It contains data collection from Yahoo Financial Services, followed by data cleaning and analysis. The project is separated into three main sections:
              - The first is the analysis of the markets in terms of returns (daily and log returns), volatility and a risk assesment followed by a market correlation.
              - The second part contains machine learning models to predict the market opening.
              - The last section is a pair trading in the technology sector - Identifying co-integrated pairs and time to entry/exit.

  - [Home Loan Approval Classification](https://rpubs.com/ptrGSKA/1078169): Classification models for acceptance for loan application outcome. The analysis started with data cleaning and imputation the detection and removal of outliers
              preparing data for prediction. This is followed by some EDA, and model building where the best performing model has achieved over 85% accuracy.
       
### R - Shiny

- __App Developement__
  
    - [Financial analysis of Global Stock Markets](https://ptrgska.shinyapps.io/financial_analysis_shiny/): Analysis of global markets as the final grduation project. This is an interactive version of the above described project.
            Shiny web app was developed at the end of the analysis.



