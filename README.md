# 🧪 Kaggle Playground Series - Season 5, Episode 5

This repository contains my solution for the [Kaggle Playground Series - S5E5](https://www.kaggle.com/competitions/playground-series-s5e5) regression competition.

🎯 **Objective:** Predict the `Calorie Expenditure` of a man.  
📏 **Evaluation Metric:** Root Mean Squared Error (RMSLE)

---

## 📁 Structure

- `Calories_pred.ipynb` — Jupyter Notebook for EDA and modeling  
- `data/` — Folder for dataset files 
- `submission.csv` — Final Kaggle submission file  
- `README.md` — This file  

---

## 🧠 My Approach

- Performed EDA and basic feature analysis
- Used `XGBoostRegressor` with `tree_method="hist"` for speed
- Tuned hyperparameters using Optuna
- Applied K-Fold cross-validation
- Clipped negative predictions before evaluation to avoid RMSLE errors
