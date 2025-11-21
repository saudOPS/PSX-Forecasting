## 📈 PSX Stock Price Forecasting: ENGRO Corporation

This project focuses on forecasting the stock prices for **ENGRO Corporation** (ENGRO) listed on the **Pakistan Stock Exchange (PSX)** using a **Linear Regression** model. The objective is to predict future closing prices and simulate the return on an investment.

---

## 🎯 Objective

The primary goals of this project are:
* **Predict stock closing prices** for specific future dates:
    * September 1, 2025
    * December 1, 2025
    * June 1, 2026
* **Simulate the return** on a hypothetical investment of **Rs. 10,000**.
* **Visualize the stock's performance** over the past four years using a **candlestick chart**.

---

## 💻 Methodology

### Data Source and Preprocessing

* **Stock Selected:** ENGRO Corporation
* **Data Source:** Pakistan Stock Exchange official website, [psx.com.pk](http://www.psx.com.pk)
* **Time Range:** Daily Open, High, Low, and Close (OHLC) price data from **January 2021 to December 2024**.
* **Cleaned Data:** The processed data is saved as `ENGRO_PSX_2021_2024.csv`.
* **Feature Used:** Only the **'Close' price** was used as the independent variable for the prediction model.

### Algorithm and Model

The prediction was performed using a simple **Linear Regression** model.

* **Why Linear Regression?**
    * It is **simple and highly interpretable**.
    * It performs **well for trend-based forecasting**.
* **Training:** The model was trained using the **number of days since the start of the data** as the independent variable against the **closing price**.

---

## 💡 Potential Improvements and Alternative Models

While Linear Regression provides a strong baseline, future iterations could incorporate more complex models and features to improve accuracy, especially for volatile stocks.

### Alternative Models
* **LSTM (Long Short-Term Memory) - Deep Learning:** This model is an alternative because it is designed to **learn temporal patterns better** than traditional linear models and **could reduce error in volatile stocks**.

### Feature Enhancements
Future model training could be enhanced by using additional features:
* **Technical Indicators:** Incorporate volume and other technical indicators.
* **Macroeconomic Indicators:** Add macroeconomic indicators.
* **Sentiment Analysis:** Incorporate news sentiment or Twitter analysis.
