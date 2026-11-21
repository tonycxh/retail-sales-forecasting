# Retail Sales Forecasting

## Project Overview
This project explores historical retail sales data from Kaggle's Store Sales - Time Series Forecasting competition and develops statistical time-series forecasting models to predict future sales.

The dataset covers 54 stores and 33 product families.

## Technologies Used
- Python
- Pandas
- Matplotlib
- SARIMA / SARIMAX
- Auto-ARIMA
- Jupyter Notebook

## Project Workflow
1. Clean and explore historical sales data.
2. Analyze seasonal trends, promotions, oil prices, and calendar effects.
3. Engineer lag and rolling-window features.
4. Develop and evaluate time-series forecasting models.
5. Generate and validate a Kaggle submission containing 28,512 predictions.

## Results
The project reports a 14.3% reduction in RMSE compared with a previous-week baseline. This result is subject to review of the validation approach and feature leakage.

## Dataset
[Kaggle Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)

## How to Run
1. Download the dataset from Kaggle.
2. Open `store-sales-time-series-forcasting.ipynb` in Jupyter Notebook or Google Colab.
3. Update the dataset file paths to match your environment.
4. Install the required Python libraries and run the notebook cells in order.

Note: The notebook uses Kaggle-specific data paths and may require adjustments outside Kaggle.

## Future Improvements
- Review time-series validation to prevent data leakage.
- Improve reproducibility with a requirements file and portable paths.
- Compare additional forecasting models.
