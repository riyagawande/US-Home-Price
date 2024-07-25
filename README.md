# US-Home-Price
# Objective: 
Find publicly available data for key factors that influence US home prices nationally. Then, build a data science model that explains how these factors impacted home prices over the last 20 years. Use the S&P Case-Schiller Home Price Index as a proxy for home prices: fred.stlouisfed.org/series/CSUSHPISA.

# Steps Involved: 
  A]  The following steps were implemented in the Dataprep.ipynb file ()
 
        1. Data Collection:
          Utilized the S&P Case-Schiller Home Price Index as a proxy for home prices, sourced from the Federal 
          Reserve Economic Data (FRED) website 

        2. Key Factors:
           Gathered publicly available data on factors influencing home prices nationally, including Per Capita GDP, 
           Consumer Price Index (CPI), Construction Material Costs, Household Income, Subsidies, and Population, etc.

        3. Data Cleaning and Processing:
           Cleaned and processed the data, addressing missing values, converting date formats, and handling outliers.

        4. Data Preparation:
           The prepared dataframe is converted into a CSV file. Refer it here (prepared_dataset.csv)


  B]   The following steps are involved in the Data Science Model.ipynb file ()

        1. Exploratory Data Analysis (EDA):
           Conducted EDA to understand the distribution of variables, identify correlations, and visualize trends over time.

        2. Model Selection:
           Explored various regression models, including Linear Regression, ElasticNet, Random Forest, Gradient Boosting, 
           Support Vector Regression (SVR), and XGBoost.

        3. Model Training and Evaluation:
          Trained each model using a subset of the data, evaluated performance using metrics such as Mean Squared Error 
          (MSE) and R-squared.

        4. Model Comparison:
           Compare the performance of different models based on metrics such as Mean Squared Error (MSE) and R-squared. 
           Select the best-performing model that provides accurate predictions and insights into the factors influencing 
           home prices over the last 20 years.

        5. Visualization:
           Create visualizations to illustrate the relationships between actual and predicted home prices for each model. 

        6. Conclusion:
           Identified strong data model for the best model, considering their low MSE and high R-squared values. 


Following Variables or Factors chosen for the study: 

1. Per Capita GDP : https://fred.stlouisfed.org/series/A939RX0Q048SBEA
2. Working Population : https://fred.stlouisfed.org/series/LFWA64TTUSM647S
3. Total households : https://fred.stlouisfed.org/series/TTLHH
4. Consumer price index (CPI) : https://fred.stlouisfed.org/series/CPIAUCSL
5. Unemployment rate : https://fred.stlouisfed.org/series/UNRATE
6. Employment rate : https://fred.stlouisfed.org/series/LREM64TTUSM156S
7. Construction price index : https://fred.stlouisfed.org/series/WPUSI012011
8. Interest rates : https://fred.stlouisfed.org/series/FEDFUNDS
9. Household Income : https://fred.stlouisfed.org/series/MEHOINUSA672N
10. Housing Subsidies (Federal) : https://fred.stlouisfed.org/series/L312051A027NBEA
11. Population above age 65 : https://fred.stlouisfed.org/series/SPPOP65UPTOZSUSA

As a proxy to the home prices, S&P CASE-SHILLER Index is used.
