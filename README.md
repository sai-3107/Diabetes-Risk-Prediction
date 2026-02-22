# Deep Learning for Type 2 Diabetes Risk Assessment
**Validation on the DiaBD-A Regional Dataset (Bangladesh)**

[cite_start]This repository contains the backend and analysis for a research chapter submitted to the Elsevier book: *"Artificial Intelligence and Computational Models in Metabolic Health."* 

## 📝 Overview
[cite_start]This project presents an advanced data-driven approach to T2DM risk assessment[cite: 4]. [cite_start]By leveraging a **Sequential Neural Network** trained on the **DiaBD-A dataset**, the model successfully identifies high-dimensional risk patterns associated with clinical and physiological indicators[cite: 4, 8].

## 🚀 Key Features & Results
* [cite_start]**Model Accuracy:** Achieved a classification **accuracy of approximately 93.6%** on the validation set[cite: 8].
* [cite_start]**Features:** Utilizes 14 distinct clinical features including pulse rate, blood pressure, BMI, and family history[cite: 6].
* [cite_start]**Methodology:** Employs a robust data pipeline including mean-imputation for missing values, normalization, and feature scaling using `StandardScaler`[cite: 7].
* **Optimized Selection:** Comparison between **Baseline Logistic Regression**, **RFE-Optimized models**, and **Deep Learning** architectures.

## 🛠️ Technology Stack
* **Core Logic:** Python (Pandas, NumPy, Scikit-learn).
* **Deep Learning:** TensorFlow / Keras (Sequential API).
* **Visualization:** Matplotlib, Seaborn.
* [cite_start]**Web Interface:** HTML/JS for cross-platform integration[cite: 9].

## 📊 Model Architecture
The core predictive engine is a **Sequential Neural Network** with:
1.  **Input Layer:** Standardized feature set.
2.  **Hidden Layer 1:** 32 Neurons (ReLU activation).
3.  **Hidden Layer 2:** 16 Neurons (ReLU activation).
4.  **Output Layer:** 1 Neuron (Sigmoid activation for binary classification).

## 📂 Dataset Citation
[cite_start]The analysis is based on the **DiaBD-A dataset**, focusing on regional clinical data from Bangladesh to enhance relevance to diverse populations[cite: 4, 5].
