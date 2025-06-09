# Breast Cancer Detection using Machine Learning and Deep Learning

## 📌 Overview

Breast cancer remains one of the most prevalent and life-threatening diseases affecting women globally. Early detection is crucial for effective treatment and improved survival rates. This project presents a detailed review and implementation of machine learning (ML) and deep learning (DL) techniques aimed at diagnosing breast cancer and leukemia using publicly available datasets.

## 🎯 Objective

To examine, evaluate, and respond to recent ML and DL advancements in cancer detection—especially for breast cancer and leukemia—by:

* Utilizing the **Breast Cancer Wisconsin Diagnostic Dataset** from [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
* Developing and comparing supervised ML models
* Identifying and leveraging impactful features that distinguish between benign and malignant diagnoses

## 🔄 Project Workflow

### Phase 1: Data Preprocessing

* Gathered and cleaned data by removing inconsistencies and errors
* Focused on differentiating between malignant and benign samples
* Prepared clean, reliable input for accurate model training

### Phase 2: Data Preparation

* Combined and randomized data to avoid bias
* Ensured balanced and representative samples for effective ML training

### Phase 3: Feature Selection

* Reduced 31 original features to the 8–9 most significant
* Selected features: `Concave Points Worst`, `Area Worst`, `Area SE`, `Texture Worst`, `Texture Mean`, `Smoothness Worst`, `Smoothness Mean`, `Radius Mean`, `Symmetry Mean`

### Phase 4: Feature Projection

* Applied dimensionality reduction techniques to simplify high-dimensional data
* Used linear and nonlinear methods to reduce noise and improve model interpretability

### Phase 5: Feature Scaling & Visualization

* Standardized feature magnitudes through scaling
* Visualized feature relationships using:

  * **Heatmaps** for correlation
  * **Scatter plots** for pairwise comparisons
  * **Histograms** for feature distribution
  * **Box plots** for statistical insights
  * **Pair plots** for multivariate exploration

## 🧠 Technologies Used

* **Python** (NumPy, Pandas, Scikit-learn)
* **Visualization**: Matplotlib, Seaborn
* **Notebook Environment**: Jupyter
* **ML Algorithms**: Logistic Regression, SVM, Decision Trees, etc.

## 📂 Dataset

* **Source**: [UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
* **Features**: 31 parameters, target variable: diagnosis (malignant or benign)

## 📊 Results (To be added)

* Model accuracy, precision, recall, and F1-score
* Visualization of performance metrics (confusion matrices, ROC curves)

## 📜 License

This project is intended for educational purposes only. Please cite original dataset authors when used in research or publications.
