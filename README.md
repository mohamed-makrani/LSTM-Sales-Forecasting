# 🏪 LSTM Sales Forecasting Dashboard

This Streamlit app uses a trained LSTM model to predict sales based on store, item, and date features.

## 📂 How to Use

1. Upload a CSV file with the following columns: `date`, `store`, `item`, `sales`.
2. The app will predict sales using a pre-trained LSTM model.
3. Visualizations (line chart, boxplot, histogram) are shown.
4. Download the prediction results as CSV.

## ⚙️ Setup

```bash
pip install -r requirements.txt
streamlit run app.py
