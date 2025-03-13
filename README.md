Sure! Here’s a template for the README file for your Git repository based on the contents you provided:

---

# Stock Price Forecasting of Netflix (NFLX) and Amazon (AMZN)

## Overview

This project investigates the prediction of Netflix (NFLX) and Amazon (AMZN) stock prices using various forecasting methods. The goal is to determine the most accurate forecasting technique for each company's stock price by comparing different approaches, including Exponential Smoothing, Weighted Moving Average, Linear Regression, and more. The performance of each model is assessed using the Mean Absolute Percentage Deviation (MAPD) to evaluate the forecast accuracy.

## Methods Used

1. **Short-term Forecasting**:
   - Visualization and trend analysis of historical stock data.
   - Application of Exponential Smoothing with various alpha values.
   - Use of adjusted exponential smoothing with trend parameters.

2. **Long-term Forecasting**:
   - Use of 3-period moving average for predictions between periods 1 and 50.
   - Application of the linear trend forecast method for predicting future stock prices.

3. **Regression Analysis**:
   - Linear regression for predicting stock values over a longer time horizon.
   - Evaluation of residuals to check for homoscedasticity and normality.

4. **Comparison and Evaluation**:
   - Comparison of MAPD values for different methods.
   - Identification of the most accurate forecasting technique for NFLX and AMZN.

## Project Details

- **Data**: Historical daily stock prices for NFLX and AMZN.
- **Forecasting Methods**: Exponential Smoothing, Weighted Moving Average, Simple Linear Regression, Linear Trend Forecast.
- **Metrics**: Mean Absolute Percentage Deviation (MAPD) to evaluate forecast accuracy.

## Key Findings

- **NFLX**: Exponential Smoothing with α = 0.50 provided the most accurate forecasts.
- **AMZN**: The optimal forecasting method is inconclusive due to high MAPD values, suggesting potential issues with data or calculations.
- **Linear Trend**: More accurate for long-term predictions compared to the Weighted Moving Average method.
- **MAPD Comparison**: The Weighted Moving Average and Simple Regression methods generally yielded higher MAPDs, indicating less accurate predictions.

## Portfolio Suggestion

In a portfolio consisting of both NFLX and AMZN stocks, a balanced allocation could be a starting point with **40% for AMZN (A = 40%)** and **60% for NFLX (N = 60%)**, but this should be adjusted based on an investor's risk tolerance, goals, and market outlook.

## Conclusion

The study concludes that Exponential Smoothing with α = 0.66 provides a reasonable forecast for NFLX stock prices, while further research is needed to improve forecasting for AMZN. A benchmark comparison method could be useful to draw more definitive conclusions.

## Requirements

To run the project locally:

- Python 3.x
- Pandas
- Numpy
- Matplotlib (for visualizations)
- Statsmodels (for regression analysis)
- Jupyter Notebook (optional for code execution)

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stock-price-forecasting.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or script for analysis:
   ```bash
   jupyter notebook stock_forecasting.ipynb
   ```

## Files Included

- `stock_forecasting.ipynb`: Jupyter notebook containing the entire forecasting analysis.
- `data/`: Folder containing the historical stock data for NFLX and AMZN.
- `results/`: Folder containing output files with forecasts and MAPD calculations.

## Future Work

- Implement additional forecasting methods (e.g., ARIMA, Prophet).
- Compare the models with a benchmark or historical averages.
- Improve data handling and computations to resolve issues with AMZN predictions.

## References

- [Exponential Smoothing in Excel](https://www.excel-easy.com/examples/exponentialsmoothing.html)
- [Mean Absolute Percentage Error (MAPE)](https://www.statisticshowto.com/mean-absolute-percentage-error-mape/)

---
