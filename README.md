# 📊 Customer Churn Prediction

This project predicts customer churn using the **Telco Customer Churn dataset**. It applies data preprocessing, feature engineering, and advanced ensemble machine learning techniques to identify customers who are most likely to leave a telecom service provider.

---

## 🚀 Project Description

- **Objective**: Predict whether a customer will churn based on their demographic, contract, and service-related details.  
- **Dataset**: Telco-Customer-Churn (cleaned CSV provided in repo).  
- **Approach**:
  - Exploratory Data Analysis (EDA)
  - Feature engineering & encoding
  - Model training using XGBoost, LightGBM, and CatBoost
  - Hyperparameter tuning with **Optuna**
  - Ensemble stacking for improved performance  
- **Result**: Final model achieves ~0.85 AUC score on the test set.  

---

## 🛠️ Tech Stack & Libraries

- **Language**: Python 3.x  
- **Core Libraries**:  
  - `scikit-learn`  
  - `xgboost`  
  - `lightgbm`  
  - `catboost`  
  - `optuna`  
  - `numpy`, `pandas`  
  - `matplotlib`, `seaborn`, `plotly`



---

## ⚙️ Requirements

Make sure you have **Python 3.x** installed. Then install the required libraries:

```bash
pip install -r requirements.txt
🗄️ Database / Data Setup
No external database required.

Data is already provided in CSV format: Telco-Customer-Churn-dataset-cleaned.csv

If needed, you can import the CSV into a database like MySQL/Postgres and update the notebook to fetch from there.


How to Run Locally
Clone the Repository

git clone https://github.com/vishred06-cmd/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
Create Virtual Environment (optional but recommended)


python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
Install Dependencies


pip install -r requirements.txt
Run the Jupyter Notebook


jupyter notebook Telco-Customer-Churn-Prediction.ipynb

👉 Alternatively, open the HTML file:
Telco-Customer-Churn-Prediction.html in your browser to view results directly.

Using Saved Models / Hyperparameters

Pre-tuned hyperparameters (.pickle files) are available for direct use.

The CatBoost model inside model_catboost/ can be loaded for predictions.

📜 License
This project is licensed under the MIT License. You are free to use, modify, and distribute with attribution.

🙌 Acknowledgements
Dataset: IBM Telco Customer Churn Dataset (commonly available via Kaggle).

Thanks to open-source contributors of Scikit-learn, XGBoost, LightGBM, CatBoost, and Optuna.


