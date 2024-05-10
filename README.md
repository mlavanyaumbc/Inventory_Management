# Inventory Management for Business Growth

## Abstract
The objective of this project is to predict total sales for 2024 year using 2019 - 2023 sales data and also to predict the inventory requirements for different product categories in the year 2024. The project intends to forecast future sales and calculate important inventory indicators, such as Economic Order Quantity (EOQ), Safety Stock, Reorder Points, and Average Inventory levels, by analyzing previous sales data. The objective is to enhance inventory management and save expenses while ensuring enough stock levels to satisfy customer demands.

## Idea
The primary objective of this project is to utilize statistical models in order to properly forecast future inventory needs. By combining time-series forecasting with inventory management concepts, we guarantee that the firm may effectively plan for future demand without having excessive or insufficient stock of products.


## About Data
The dataset used for this research comprises historical sales data that encompasses last five years from 2019 to 2023. The dataset comprises daily transaction records for several item categories, Material categories , detailing the sales volume, sales price, and transaction date and total sale. This dataset enables in-depth time-series analysis for predicting sales patterns for 2024 year sales.

## Source of Data

Company Name : Charm City Gold & Diamonds

Address : Hanover, MD 21076, 7000 Arundel Mills Cir space 167, Charm City, Gold and Diamond

Data Format : .XLS Format

Size : 5 years’ data (app. 13,000 Rows)

![image](https://github.com/mlavanyaumbc/Inventory_Management/assets/112786869/98654daf-2992-4838-8c48-6da9a50182c4)


## Research Questions

#### 1. Which Machine Learning models are most effective for analyzing jewelry sales data and predicting future demand patterns?
Using the SARIMA models, our forecasts based on historical sales data showed RMSE (Root Mean Square Error) of 5176.70 , MAE
(Mean Absolute Error) of 26798303.79, and R2 (R Squared score) of 0.733, indicating a medium level of accuracy in predicting
future sales. Also,upon incorporating date-time variables tried Machine learning models like Random Forest model, Gradient
Boosting ,XG Boosting, and some ensembling and stacking techniques to improve accuracy of predictions.

#### 2. How can clustering algorithms be utilized to group similar jewelry items together for efficient inventory management?
Clustering algorithms effectively grouped jewelry items into distinct categories that facilitated differentiated
inventory management strategies. Clustering by sales volume and material type helped identify high-demand items requiring
more dynamic stocking policies. This strategic grouping allowed for more precise inventory control, reducing overstock and
understock by thereby optimizing overall inventory levels and reducing associated costs.

#### 3. How can inventory levels be optimized to ensure sufficient stock of high-demand items while minimizing excess inventory and costs?
Optimizing inventory levels for each item and material involves precise demand forecasting, strategic safety stock
calculations, and timely reorder points. By utilizing advanced analytics and machine learning models, businesses can
dynamically adjust inventory to meet consumer demand efficiently, thus minimizing costs and avoiding excess stock.

## Exploratory Data Analysis
The exploratory data analysis (EDA) phase involved:
- Visualizing sales trends over time to understand seasonal variations and demand patterns.
- Analyzing sales distributions and correlations between different item categories.
- Identifying outliers and anomalies that could impact the predictive model's accuracy.
- Detected and replaced in missing values to enhance the reliability of the dataset.
- Identified and resolved anomalies by utilizing box plots and statistical criteria.
- Generated time series plots for each product category to examine sales patterns over time.
- Analyzed time series data by decomposing it to isolate seasonal fluctuations and evaluate their influence on sales.
- Employed heatmaps to investigate the associations between various factors in the dataset.
- Presented summary statistics for sales data to analyze measures of central tendency and dispersion.

## Implementation

This project is implemented using Python, making use of many robust modules to efficiently handle data processing, visualization, and statistical modeling. Below is a more comprehensive analysis:

#### 1.Data Exploration and Cleaning Process
* Initial data exploration: Assessing data quality, identifying missing values, understanding feature distribution.
* Data cleaning: Using Pandas, handling missing data, correcting data types, addressing outliers.
* Techniques: Data transformation, normalization, standardization for dataset preparation.

#### 2.Data Analysis Visualization
* Utilizes Matplotlib and Seaborn for plot creation.
* Uses histograms, box plots, scatter plots, bar charts.
* Implements advanced visualizations like heatmaps for correlation matrices and pair plots for multivariate analysis.

#### 3. Statistical and Machine Learning Modeling and Forecasting

**Statistical Models**:
    The project leverages `Statsmodels` for comprehensive statistical modeling. Time series analysis, particularly using ARIMA/SARIMA models, plays a central role in forecasting future demands based on historical data. These models are chosen for their ability to account for trends, seasonality, and autocorrelation in time series data.
    Model diagnostics and validation are rigorously performed to ensure the accuracy of these models. This involves analyzing residuals, checking fit statistics, and evaluating predictive accuracy through performance metrics like RMSE (Root Mean Square Error) and MAE (Mean Absolute Error).

**Machine Learning Models**:
    In addition to statistical models, the project implements machine learning techniques using libraries such as `scikit-learn` for more dynamic predictions. Models like Random Forest, Gradient Boosting, and possibly neural networks are used to capture complex nonlinear relationships in the data.
    These models are trained using historical data, with features engineered from the datasets to improve predictive performance. Hyperparameter tuning is conducted using methods like Grid Search or Random Search to optimize the models.
    The effectiveness of the machine learning models is also assessed through cross-validation and performance metrics, ensuring that the models generalize well to new, unseen data.

**Integration of Models**:
    The project may also explore ensemble methods to combine the predictions from both statistical and machine learning models, aiming to leverage the strengths of each approach to enhance overall forecast accuracy.
    The integration is done in a manner that the output from one model can be used as an input to another, or by averaging predictions from multiple models to reduce variance and bias.

## Final Analysis

The final analysis includes:
**Time-Series Forecasting**: Implementation of SARIMA models to predict future sales for each item category. The models were selected based on AIC scores and diagnostics checks.
**Inventory Calculations**:
  - **EOQ (Economic Order Quantity)**: Calculation of the optimal order quantity that minimizes the total holding costs and ordering costs.
  - **Safety Stock**: Determination of an ideal stock level that accounts for demand variability during the lead time.
  - **Reorder Point**: Establishing the minimum stock level at which an order should be placed to replenish the inventory.
  - **Average Inventory**: Estimating the average stock level needed to maintain service levels without excessive overstock.


## Results
The models provided reliable sales forecasts which were translated into actionable inventory metrics. The outcomes are visualized in several plots and tables to demonstrate the forecast accuracy and inventory recommendations for each product category.
![image](https://github.com/mlavanyaumbc/Inventory_Management/assets/112786869/6c7ac12f-d30a-46f8-a614-565349e95b02)
![image](https://github.com/mlavanyaumbc/Inventory_Management/assets/112786869/11e0670c-b46d-4b02-b841-7e4535ad8789)
![image](https://github.com/mlavanyaumbc/Inventory_Management/assets/112786869/31337ab4-5c66-46b8-b444-dc59d8a5e2dc)
![image](https://github.com/mlavanyaumbc/Inventory_Management/assets/112786869/281ae066-70b2-4b13-84f6-8cd0a72cad11)
![image](https://github.com/mlavanyaumbc/Inventory_Management/assets/112786869/78197aa1-1ba1-4c08-aa87-6ab577d2e02b)





## Conclusions
The predictive models and inventory calculations deliver valuable insights for effective inventory management. By applying these methodologies, businesses can ensure optimal inventory levels that align with future sales forecasts, reducing the costs associated with excess inventory and stockouts.

## Dashboard
![image](https://github.com/mlavanyaumbc/Inventory_Management/assets/112786869/8f25f5e5-8394-4094-956b-b1740728d5bc)

