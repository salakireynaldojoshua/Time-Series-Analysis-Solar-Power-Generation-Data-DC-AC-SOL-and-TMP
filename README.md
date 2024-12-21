# Time Series Analysis of Solar Power Generation Data  

This project explores time series analysis of solar power generation data using the `pv_2years_eng.csv` dataset. The analysis involves decomposing the time series, ensuring stationarity, and implementing forecasting models like moving averages, triple exponential smoothing, and autoregression. The results are presented visually with plots to better understand trends, seasonality, and residual components.  

---

## 📊 Dataset Overview  
The `pv_2years_eng.csv` dataset comprises **17 columns** representing various parameters related to a photovoltaic (PV) system. These include:  
- **DC Data**:  
  - `DC_V`: DC Voltage  
  - `DC_A`: DC Current  
  - `DC_W`: DC Output  
- **AC Data**:  
  - `AC_V_RS`, `AC_V_ST`, `AC_V_TR`: AC Voltage (R-S, S-T, T-R phases)  
  - `AC_A_R`, `AC_A_S`, `AC_A_T`: AC Current (R, S, T phases)  
  - `AC_W`: AC Output  
  - `AC_TOT`: AC Cumulative Power Generation  
  - `AC_FREQ`: AC Frequency  
  - `AC_POW`: AC Power Factor  
- **Environmental Data**:  
  - `SOL_RAD_SLOPE`: Solar Radiation Slope (W/㎡)  
  - `SOL_RAD_LEVEL`: Horizontal Solar Radiation (W/㎡)  
  - `TMP_MODU`: Module Temperature (℃)  
  - `TMP_CLI`: Outdoor Temperature (℃)  

These parameters collectively provide insights into the PV system's performance and environmental conditions.

---

## 🛠️ Project Objectives  
1. **Time Series Decomposition**:  
   - Decompose the time series data into trend, seasonal, and residual components.  
   - Compare the results using additive and multiplicative models.  

2. **Stationarity Analysis**:  
   - Calculate the first-order difference of the time series to ensure stationarity.  
   - Use **Statsmodels**' `acf()` and `pacf()` functions to calculate and plot autocorrelation and partial autocorrelation lags.  

3. **Forecasting Models**:  
   - **Moving Average (MA)**: Implement and display predictions using the moving average technique.  
   - **Triple Exponential Smoothing**: Apply triple exponential smoothing and visualize the results.  
   - **Autoregressive (AR)**: Develop an autoregressive model and present the outcomes with plots.  

4. **Time Prediction Units**:  
   - Explore possible time prediction units, including minutes, hours, days, months, quarters, and years.  
   - Use data augmentation if necessary to handle insufficient data for annual forecasts.  

---

## 🚀 Implementation Details  
- **Tools and Libraries**:  
  - Jupyter Notebook for code execution.  
  - Python libraries: `pandas`, `numpy`, `matplotlib`, `statsmodels`, and `seaborn`.  
- **Submission Format**:  
  - Jupyter Notebook (`.ipynb`) and PDF file.  
- **Data Sources**:  
  - [Download Dataset File 1](https://drive.google.com/file/d/1y69rxDxg9DbECixU-IWUgtbEP8Hzsk2V/view?usp=drive_link)  
  - [Download Dataset File 2](https://drive.google.com/file/d/1d9XF7-XxFbQl8IZUwZz2uirRyYoQvuDp/view?usp=drive_link)  
  - [Additional File](https://drive.google.com/file/d/1wAQiIxpM2xNJg-7f792IvH1tmKP_WS4Y/view?usp=sharing)  

---

## 📉 Key Results  
1. **Decomposition Results**: Visualizations showcasing the trend, seasonality, and residuals using both additive and multiplicative models.  
2. **Stationarity Verification**: Plots of autocorrelation and partial autocorrelation lags to confirm stationarity.  
3. **Forecasting Performance**: Predictions using MA, triple exponential smoothing, and AR models with visual comparisons.  
4. **Efficiency**: Analysis of time prediction units and their impact on forecasting accuracy.  

---

## 🔗 References  
- `pv_2years_eng.csv` dataset.  
- Tools: [Statsmodels Documentation](https://www.statsmodels.org/stable/index.html), [Matplotlib](https://matplotlib.org/).  
- Additional data files:  
  - [Dataset File 1](https://drive.google.com/file/d/1y69rxDxg9DbECixU-IWUgtbEP8Hzsk2V/view?usp=drive_link)  
  - [Dataset File 2](https://drive.google.com/file/d/1d9XF7-XxFbQl8IZUwZz2uirRyYoQvuDp/view?usp=drive_link)  
  - [Additional File](https://drive.google.com/file/d/1wAQiIxpM2xNJg-7f792IvH1tmKP_WS4Y/view?usp=sharing)  

---

## 📂 Repository Features  
- **Code**: Includes Jupyter Notebooks for each analysis step.  
- **Data**: Download links for the `pv_2years_eng.csv` dataset.  
- **Documentation**: Detailed explanations of methods and results.  

---

## 🤝 Contributions  
Contributions are welcome! Submit a pull request or open an issue to suggest enhancements.  

---

## 🔗 Contact  
For questions or collaboration opportunities, feel free to reach out.  
