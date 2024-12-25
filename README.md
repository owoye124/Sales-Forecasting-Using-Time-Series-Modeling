# Sales Forecasting for Supply Chain Optimization Using Time Series Modeling

## Project Overview
This project addresses the challenge of sales forecasting in supply chain management using historical data from the DataCo Supply Chain dataset. Accurate sales predictions enable businesses to optimize inventory, reduce operational costs, and enhance customer satisfaction. The project employs time series modeling techniques to predict future sales and provide actionable insights for decision-making.

## Dataset
The dataset used for this project is the **DataCo Supply Chain Dataset**, which contains detailed information about transactions, customer demographics, product details, shipping, and sales. Key features include:

- **Order Date**: The date of the transaction.
- **Sales**: Revenue generated from each order.
- **Shipping Mode**: Delivery method used.
- **Late Delivery Risk**: Binary indicator of late deliveries.
- And many other fields related to customer, product, and geographic details.

The dataset is accompanied by a description file that explains each field in detail.

## Objectives
1. Analyze historical sales data to understand trends and patterns.
2. Build a time series model to forecast future sales.
3. Provide insights and recommendations for supply chain optimization based on the forecasts.

## Methodology
### 1. Data Preprocessing
- The dataset was cleaned and filtered to focus on the **Order Date** and **Sales** columns.
- Missing values and anomalies were handled appropriately.
- The data was converted into a time series format for analysis.

### 2. Exploratory Data Analysis (EDA)
- Visualized sales trends over time to identify seasonality and patterns.

### 3. Modeling
- Built a time series model using historical sales data.
- Split data into training and test sets to validate model performance.
- Evaluated the model using metrics such as similarity score and residual plots.

### 4. Forecasting
- Forecasted sales for the next 20 days using the trained model.
- Visualized the forecast to highlight expected trends and potential risks.

## Results
- The time series model provided accurate predictions for future sales.
- Key patterns, such as seasonal variations and sales spikes, were identified.


## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory and install dependencies.
3. Open the Jupyter notebook (`Supply chain project Implementation.ipynb`) to view the analysis and results.




