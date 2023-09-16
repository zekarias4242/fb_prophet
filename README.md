# Time Series Forecasting with Facebook Prophet

This project demonstrates time series forecasting using Facebook Prophet on Apples stock price.
## Overview

In this project, we perform the following main steps to forecast time series data:

1. **Data Preparation:**
   - historical time series data, which is a crucial step in any forecasting task.
   - The data have two columns: a time/date column and a target variable column which is stock price.

2. **Data Exploration:**
   - Before applying the forecasting technique, Explored the dataset to understand its characteristics.

3. **Model Training:**
   - Fiting the Prophet model to the training data using the `Prophet.fit()` method.

4. **Forecasting:**
   - Used the trained model to make future forecasts.
   - The `make_future_dataframe()` function helps generate a dataframe with future dates.

5. **Plotting and Visualization:**
   - Made Visualization to the historical data and forecasted values using Matplotlib library.
   - This step helps in assessing the accuracy of the forecast.

## Getting Started

Follow these steps to run the code and replicate the forecasting process:

1. Clone the repository: `git clone <https://github.com/zekarias4242/fb_prophet.git>`

2. Prepare your time series data and ensure it has the necessary columns (e.g., 'ds' for dates and 'y' for target values).

3. Modify the Prophet model configuration in the code to fit your dataset and forecasting requirements.

4. Run the code and follow the prompts to visualize and evaluate the forecasts.

## Dependencies

- Python 3.x
- Prophet (Facebook Prophet library)
- Matplotlib (for data visualization)

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Facebook Prophet: [https://facebook.github.io/prophet/](https://facebook.github.io/prophet/)
- yahoo finance public dataset 
