# 📈 Volatility Curve Prediction & Analysis

> **NK Securities Research Challenge (1–8 June 2025)**  
> 📍 Kaggle-style Competition • 🧠 Data Imputation • 🏦 Financial Modeling

---

## 👨‍💻 Author

**Nitin Kumar**  
Indian Institute of Technology Kharagpur  
<a href="https://www.linkedin.com/in/nitin-kumar-3722212ab/" target="_blank">🔗 LinkedIn</a> |
<a href="https://github.com/samosa1610/NK-volatility-prediction/blob/main/NKSR2025_Volatility_Prediction_Report.pdf" target="_blank">📄 Final Report (PDF)</a>


---

## 📦 Project Structure

📁 approach_1/  
→ Two-Phase Imputation (Baseline)

📁 approach_2/  
→ Enhanced Multi-Phase Imputation

📁 approach_3/  
→ ML-Enhanced Advanced Imputation

📁 approach_4/  
→ Iterative Imputation with Random Forest

📁 submissions/  
→ Organized submissions

📄 EDA_results.html  
→ Exploratory Data Analysis output

📄 NKRC2025_Volatility_Prediction_Report.pdf  
→ Final project report

📄 README.md  
→ This file

---

## 🎯 Project Objective

> Develop and evaluate imputation strategies to reconstruct missing option volatility curve data using advanced machine learning and statistical methods.  
> Goal: **Minimize the validation MSE** over synthetic missing value regions.

---

## 🧪 Approaches Implemented

| 🧩 Approach # | Technique                     | Key Highlights                                         | 📉 MSE Score |
|--------------|-------------------------------|--------------------------------------------------------|--------------|
| **1**        | Two-Phase Imputation           | Baseline mean/forward-fill hybrid                      |  9.383102555    |
| **2**        | Multi-Phase Imputation         | Layered logic for temporal and asset-wise context      | 0.002422300    |
| **3**        | ML-Enhanced Imputation         | LightGBM and ensemble models                           |  0.000047920    |
| **4**        | Iterative Imputation (RF)      | Random Forest Regressor via `IterativeImputer`        |  0.000001056     |


---

<details>
  <summary>🧮 <strong>Evaluation Metric</strong> (click to expand)</summary>

The evaluation metric for this challenge is the **Mean Squared Error (MSE)**, defined as:

  ![image](https://github.com/user-attachments/assets/6699fcdc-a1f0-48fa-a4d5-b41c88c9a213)

  
  Where:
  - **N** is the number of unmasked implied volatility (IV) entries in the test set  
  - **𝑦̂ᵢ** is the predicted implied volatility  
  - **𝑦ᵢ** is the ground-truth implied volatility  
  
  🔍 Lower MSE values indicate better model performance in reconstructing the volatility surface.


</details>

---

## 🧠 Insights & Contributions

✅ Strong performance boost with ML-assisted imputation  
📉 Clear reduction in validation MSE from Approach 1 → 4  
🔍 EDA revealed temporal clusters of missingness  
📚 Suggested ensemble-driven iterative refinements for future work

---

## 📌 References & Tools

- 📚 `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `LightGBM`  
- 🗂️ Internal NKRC 2025 Dataset *(confidential)*  
- 🔗 [Kaggle Competition: NK IV Prediction](https://www.kaggle.com/competitions/nk-iv-prediction/)

---

## 📫 Contact

For queries or collaboration:
> 📧 nitin.kumar@kgpian.iitkgp.ac.in  
> 🔗 [GitHub](https://github.com/) | [LinkedIn](https://linkedin.com/in/nitin-iitkgp)

---

