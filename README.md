# 🤖 100 Days of Machine Learning

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)]()
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ready-orange)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-yellow)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green)]()

A complete, practice-first **100-day ML course** with daily notebooks and projects.  
Starts from zero → ends with real deployments and competition-style solutions. ✨

---

## 🗂️ Repository Layout
100-days-of-machine-learning/
├─ README.md
├─ requirements.txt
├─ curriculum/ # daily lessons (Day_001 … Day_100)
├─ projects/
│ ├─ 00_beginner/
│ ├─ 01_intermediate/
│ └─ 02_advanced/
├─ data/
│ ├─ raw/ # (gitignored) original datasets
│ ├─ processed/ # (gitignored) cleaned features
│ └─ sample/ # tiny CSVs for quick runs
├─ models/ # (gitignored) saved models
└─ images/ # screenshots / diagrams

## 📅 100-Day Curriculum (high-level)

- **Days 1–10:** Python for data, NumPy, Pandas, plots 📊  
- **Days 11–20:** EDA, data cleaning, feature engineering 🧹  
- **Days 21–35:** Supervised learning I — linear/logistic regression, kNN, Naive Bayes  
- **Days 36–50:** Supervised learning II — trees, ensembles (RF, GBM, XGBoost, LightGBM, CatBoost) 🌲  
- **Days 51–60:** Model selection — CV, pipelines, hyper-param tuning (Grid/Random/Optuna style) 🎯  
- **Days 61–70:** Unsupervised — k-means, GMM, PCA, t-SNE/UMAP, anomaly detection  
- **Days 71–80:** NLP basics — text cleaning, TF-IDF, classical ML for text; intro to word embeddings 📝  
- **Days 81–85:** Time series — train/val splits, statsmodels, feature lags, Prophet-style workflow ⏱️  
- **Days 86–90:** Computer vision basics — image datasets, augmentation, transfer learning (torch/tf) 🖼️  
- **Days 91–95:** MLOps lite — experiment tracking, metrics, model persistence, reproducibility  
- **Days 96–100:** Deployment — FastAPI/Flask service, Docker basics, batch vs realtime serving 🚀

- ## 🧪 Projects (simple → advanced)

### 00_beginner
- **Iris Classifier** 🌸 — classic multi-class basics  
- **Titanic Survival** 🚢 — feature engineering + baseline models  
- **House Prices (mini)** 🏠 — regression, CV, error analysis

### 01_intermediate
- **Customer Churn** 📞 — class imbalance, ROC/PR, calibration  
- **Credit Risk** 💳 — pipeline + thresholding + AUC optimization  
- **Job Salaries NLP** 📝 — TF-IDF + linear models + error analysis  
- **Retail Forecast** 🛒 — time-series features + validation windows

### 02_advanced
- **Toxic Comments NLP** 💬 — text cleaning, embeddings, advanced CV  
- **Plant Disease Vision** 🌿 — transfer learning + augmentation  
- **Fraud Detection** 🕵️ — anomaly detection + precision@k  
- **Tabular Competition** 🏆 — stacked models, feature selection, SHAP

Each project folder includes: `README.md`, notebook(s), and a `report.md` with metrics & learnings.

---

## 🚀 Quick Start

```bash
git clone https://github.com/mkhalidanwar777/100-days-of-machine-learning.git
cd 100-days-of-machine-learning
pip install -r requirements.txt
jupyter lab
Open any notebook under curriculum/Day_XXX or a project inside projects/ and run ▶️

📎 Datasets
Small samples live in data/sample/ for quick tests.
Place full datasets in data/raw/ (gitignored).
Recommended sources: Kaggle, UCI, Hugging Face Datasets.

🌟 What you’ll practice
Clean EDA → solid baselines → tuned models

Feature engineering & robust validation

Interpreting models (Permutation, SHAP)

Reproducible experiments and simple deployment

🙌 Contributing
Ideas, fixes, or new projects are welcome!
Open an issue or PR with a short description. 📝

📜 License
MIT — learn freely, build boldly. 😄

yaml
Copy code

---

### Optional `projects/README.md` (mini index)

```markdown
# 🧪 Project Gallery

| Level | Project | Type | Key Skills |
|------:|--------|------|-----------|
| Beginner | Iris Classifier | Classification | Baselines, metrics |
| Beginner | Titanic Survival | Classification | Feature engineering |
| Beginner | House Prices (mini) | Regression | CV, error analysis |
| Intermediate | Customer Churn | Classification | Imbalance, PR curves |
| Intermediate | Credit Risk | Classification | Pipelines, AUC |
| Intermediate | Job Salaries NLP | NLP Regression | TF-IDF, text prep |
| Intermediate | Retail Forecast | Time Series | Sliding windows |
| Advanced | Toxic Comments | NLP | Embeddings, CV |
| Advanced | Plant Disease Vision | CV | Transfer learning |
| Advanced | Fraud Detection | Anomaly/Cls | Precision@k |
| Advanced | Tabular Competition | Mixed | Stacking, SHAP |
