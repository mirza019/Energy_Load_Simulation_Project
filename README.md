# ⚡ Energy Load Forecasting and Critical Scenario Simulation

**Author:** Mirza Shaheen Iqubal  

This repository demonstrates a combined **data analysis and simulation workflow** for energy systems. It integrates **time-series forecasting** using LSTM models with **climate-energy scenario analysis**, reflecting real-world challenges in energy grid management.

---

## 📌 Project Overview
The notebook covers:
1. **Data Integration**  
   - Historical energy load data  
   - Weather/climate data (temperature & humidity)  

2. **Exploratory Analysis**  
   - Correlation analysis between load and climate conditions  

3. **Scenario Simulation**  
   - Identification of *critical grid stress* conditions (high load + extreme temperature)  
   - Monthly analysis of critical event frequency  

4. **Forecasting with LSTM**  
   - Deep learning model to predict future energy load  
   - Scaled and sequence-based time-series input  

---

## 🔬 Methods & Tools
- **Python Libraries**:  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `keras`  

- **Modeling**:  
  - LSTM for time-series load forecasting  
  - Threshold-based scenario detection  

- **Evaluation**:  
  - Correlation heatmaps  
  - Monthly stress-event counts  
  - Forecast visualization  

---

## 📊 Key Insights
- **Climate–Load Link**: Temperature and humidity significantly correlate with grid load.  
- **Critical Scenarios**: Coincidence of peak demand and extreme weather creates stress conditions.  
- **Forecasting**: LSTM effectively captures temporal patterns for short-term load prediction.  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
2. pip install -r requirements.txt
3. Place datasets in the /data directory:

energy_dataset.csv

weather_features.csv
