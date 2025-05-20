🧠 Medical Cost Prediction using Regression Models
This project focuses on predicting individual medical insurance charges using various regression models. The dataset used is sourced from Kaggle, and the target variable (charges) is a continuous numerical feature representing the medical costs billed by health insurance.

🔍 Models Evaluated
The following regression algorithms were implemented and evaluated:

📈 Decision Tree Regressor

🌲 Random Forest Regressor

⚠️ Logistic Regression (included for comparison; not ideal for continuous target variables)

🚀 XGBoost Regressor

🐱 CatBoost Regressor

🛠️ Hyperparameter Tuning
Model optimization was carried out using GridSearchCV, enabling systematic tuning of hyperparameters for each model.

✅ Results
The CatBoost Regressor achieved the best performance with an R² score of ~85%, making it the most effective model for this regression task.

📁 File Structure
predictions.ipynb — Contains the complete implementation, from data preprocessing to model training, evaluation, and hyperparameter tuning.