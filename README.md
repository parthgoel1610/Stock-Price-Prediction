# 📈 Stock Price Prediction

This project focuses on predicting **Tesla's stock prices** using deep learning techniques. It employs **Long Short-Term Memory (LSTM)** networks to capture temporal dependencies in historical stock price data, ensuring accurate forecasting.

## 🚀 Features
1. Data preprocessing and normalization using Min-Max scaling.
2. Sequence generation to feed time-dependent data into the LSTM model.
3. LSTM model architecture with dropout layers to prevent overfitting.
4. Visualization of actual vs. predicted stock prices.

## 🗂️ Dataset
- **File:** `Tesla_Stock.xlsx`
- **Target Variable:** `Close` price

## ⚙️ Installation
```bash
pip install numpy pandas matplotlib scikit-learn keras
```

## 📊 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd stock-price-prediction
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Stock_Price_Prediction.ipynb
   ```

## 📈 Model Summary
- **Model:** LSTM with 2 hidden layers
- **Optimizer:** Adam
- **Loss Function:** Mean Squared Error (MSE)
- **Epochs:** 50
- **Batch Size:** 32

## 📋 Results
The model effectively predicts Tesla's stock prices, with a clear visualization of actual vs. predicted values, showcasing its capability in time series forecasting.

## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## 📜 License
This project is licensed under the MIT License.
