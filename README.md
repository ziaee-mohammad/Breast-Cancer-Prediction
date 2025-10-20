# 🎗️ Breast Cancer Prediction using Machine Learning

A supervised **machine learning** project that predicts whether a breast tumor is **benign** or **malignant** using diagnostic features from cell nuclei.  
The project demonstrates a clean end-to-end ML workflow — from **data preprocessing** to **model training** and **evaluation** — on the classic **Breast Cancer Wisconsin dataset**.

---

## 🔍 Overview
- Load and preprocess diagnostic data from the sklearn dataset.  
- Split data into **training** and **testing** sets.  
- Train multiple machine learning models (e.g., Logistic Regression, SVM, Random Forest).  
- Evaluate model performance using **accuracy**, **confusion matrix**, and **classification report**.  
- Visualize key insights and predictions.

---

## 🧠 Models Used
- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree / Random Forest *(optional)*

---

## 🗂 Dataset
Dataset Source: **Breast Cancer Wisconsin (Diagnostic) Dataset**  
- **Features:** mean radius, texture, perimeter, area, smoothness, etc.  
- **Target:** 0 → *Malignant*, 1 → *Benign*  

> Available directly via `sklearn.datasets.load_breast_cancer()`.

---

## 📈 Results
- Achieved accuracy above **95%** on test data.  
- The model effectively distinguishes between benign and malignant samples.  
- Logistic Regression provides interpretable and stable results for medical datasets.

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/ziaee-mohammad/Breast-Cancer-Prediction-ML.git
   ```
2. Open and run the notebook:
   ```bash
   jupyter notebook
   ```
3. Explore the results and visualizations inside the notebook output.

---

## 🗃 Repository Structure
```
Breast-Cancer-Prediction-ML/
├─ data/                     # (optional) dataset or saved CSVs
├─ notebooks/                # Jupyter notebooks
├─ outputs/                  # figures and model reports
└─ README.md
```

---

## 📊 Key Insights
- Early detection of breast cancer is crucial for treatment success.  
- Feature normalization significantly improves ML performance.  
- Linear models can achieve high accuracy on small medical datasets.

---

## 📜 License
MIT — free to use and modify with attribution.

---

## 👤 Author
**Mohammad Ziaee** — Computer Engineer | Data & AI Enthusiast  
📧 moha2012zia@gmail.com  
🔗 [GitHub Profile](https://github.com/ziaee-mohammad)
👉 Instagram: [@ziaee_mohammad](https://www.instagram.com/ziaee_mohammad/)


