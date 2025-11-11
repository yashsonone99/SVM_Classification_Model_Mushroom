# SVM_Classification_Model_Mushroom
“Predicting mushroom edibility using Support Vector Machine (SVM) a robust classification model with detailed preprocessing, PCA visualization, and kernel comparison.” 🍄⚙️
# 🍄 Mushroom Classification using Support Vector Machine (SVM)

> “A robust machine learning project that classifies mushrooms as edible or poisonous using various SVM kernels, supported by PCA visualization and GridSearch optimization.”

---

## 💡 Project Overview  
This project demonstrates how the **Support Vector Machine (SVM)** algorithm can effectively classify mushrooms based on their characteristics.  
It includes **data preprocessing**, **EDA**, **model training**, **hyperparameter tuning**, and **kernel performance comparison** to find the most optimal SVM configuration.

---

## 🎯 Objectives  
- Perform **EDA** to understand feature distributions  
- Encode categorical features using **LabelEncoder**  
- Implement **SVM** with multiple kernels  
- Apply **PCA** for dimensionality reduction and visualization  
- Tune hyperparameters with **GridSearchCV**  
- Compare and evaluate different kernel performances  

---

## ⚙️ Technologies Used  
| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python |
| ML Algorithm | Support Vector Machine (SVM) |
| Libraries | pandas, numpy, seaborn, matplotlib, scikit-learn |
| Visualization | PCA, seaborn bar plots |
| Platform | Google Colab / Jupyter Notebook |

---

## 📂 Files Included  

| File | Description |
|------|-------------|
| `SVM.ipynb` | Main notebook implementing SVM on Mushroom dataset |
| `mushroom.csv` | Dataset file (input data) |
| `README.md` | Documentation for the project |

---

## 🧪 Key Steps  

### 1️⃣ Data Loading & Exploration  
- Loaded **mushroom dataset** and checked shape, info, and missing values  
- Displayed class distribution for **edible vs poisonous** mushrooms  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Visualized distributions of categorical variables  
- Generated a **correlation heatmap** (after label encoding)  

### 3️⃣ Data Preprocessing  
- Encoded all categorical features using **LabelEncoder**  
- Split dataset into **train (80%)** and **test (20%)** subsets  

### 4️⃣ Model Training  
- Implemented **SVM (RBF kernel)** using `sklearn.svm.SVC`  
- Trained and predicted on the test dataset  

### 5️⃣ Model Evaluation  
- Calculated **Accuracy, Precision, Recall, and F1-score**  
- Displayed a detailed **Classification Report**

### 6️⃣ PCA & Visualization  
- Applied **PCA (2D)** for dimensionality reduction  
- Visualized decision boundaries using contour plots  

### 7️⃣ Hyperparameter Tuning  
- Used **GridSearchCV** to tune kernel, C, and gamma values  
- Identified and tested the **best SVM model configuration**

### 8️⃣ Kernel Comparison  
- Compared performance across **Linear, Poly, RBF, and Sigmoid** kernels  
- Visualized results using a grouped **bar chart**

---

## 📊 Model Performance Summary  

| Metric | Before Tuning | After Tuning |
|---------|----------------|---------------|
| Accuracy | ~0.98 | ~0.99 |
| Precision | ~0.97 | ~0.99 |
| Recall | ~0.98 | ~0.99 |
| F1-Score | ~0.98 | ~0.99 |

> 💡 **Insight:** The RBF kernel achieved the highest performance, handling non-linear relationships effectively.  
> Polynomial and sigmoid kernels performed slightly lower due to dataset complexity.

---

## 🖼️ Visual Outputs  
Include these visuals in your repository:
- 🍄 **Class Distribution Plot (Edible vs Poisonous)**  
- 📈 **Feature Distribution Countplots**  
- 🔥 **SVM Decision Boundary (via PCA)**  
- 🎯 **Kernel Performance Comparison Bar Chart**

---

## 🚀 How to Run  

1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/SVM_Classification_Model_Mushroom.git
   cd SVM_Classification_Model_Mushroom
