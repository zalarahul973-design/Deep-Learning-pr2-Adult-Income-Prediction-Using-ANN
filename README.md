# 💰 Adult Income Prediction Using Artificial Neural Network (ANN)

<p align="center">
  🤖 <b>Deep Learning</b> •
  🧠 <b>Artificial Neural Networks</b> •
  📊 <b>Binary Classification</b> •
  ⚙️ <b>Model Optimization</b> •
  🎯 <b>Income Prediction</b>
</p>

---## 🏷️ Skills & Technologies

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/Deep%20Learning-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ANN-Neural%20Network-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Jupyter-FA0F00?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/EDA-Data%20Analysis-green?style=for-the-badge" />
</p>

---

## 📌 Project Overview

🧠 This project develops and evaluates **Artificial Neural Network (ANN)** models to predict whether an individual's annual income is above or below **$50,000**, using the Adult Census Income dataset.

🎯 **Target Classification:**

- 🔵 **`<=50K (0)`** — Income is less than or equal to $50,000.
- 🟢 **`>50K (1)`** — Income is greater than $50,000.

🚀 The project follows an end-to-end deep learning workflow, including:

- 🧹 Data Cleaning & Preprocessing
- 🔍 Exploratory Data Analysis (EDA)
- 🛠️ Feature Engineering
- 🔠 One-Hot Encoding
- 📏 Feature Scaling
- 🧠 ANN Model Building
- 🏋️ Model Training & Validation
- 📊 Model Evaluation
- ⚙️ Hyperparameter Optimization

🔬 The notebook investigates different deep learning techniques:

- ⚡ Activation Functions: ReLU, Tanh, Sigmoid, ELU
- 🏗️ Weight Initializers: Glorot, He, Zeros
- ⚖️ Loss Functions: Binary Cross-Entropy, MSE, Weighted BCE, Focal Loss
- 🔄 Batch Normalization
- 🚀 Optimizers: SGD, Momentum, RMSprop, Adam
- 🎚️ Learning Rate Sensitivity

---

## 🎯 Project Objectives

- 📂 Load and inspect the Adult Income dataset.
- 🧹 Handle missing values represented by `?`.
- 🗑️ Remove redundant columns (`fnlwgt` and `education`).
- 🎯 Encode the income target into binary labels.
- 📊 Perform Exploratory Data Analysis (EDA).
- 🔠 Apply One-Hot Encoding to categorical features.
- 📏 Scale numerical features using `StandardScaler`.
- ✂️ Split data using stratified train-test splitting.
- 🧠 Build a reusable ANN model using TensorFlow/Keras.
- ⚡ Compare ReLU, Tanh, Sigmoid, and ELU activation functions.
- 🏗️ Compare Glorot, He, and Zero weight initialization.
- ⚖️ Evaluate different loss functions.
- 🔄 Analyze Batch Normalization techniques.
- 🚀 Compare SGD, SGD with Momentum, RMSprop, and Adam.
- 🎚️ Study learning-rate sensitivity.
- 📈 Evaluate models using Accuracy, Precision, Recall, F1-score, ROC-AUC, and Confusion Matrix.




## 🛠️ Technologies Used

| 💻 Technology | 🎯 Purpose |
|:---|:---|
| 🐍 **Python** | Programming and model development |
| 🐼 **Pandas** | Data cleaning, manipulation, and analysis |
| 🔢 **NumPy** | Numerical operations and array processing |
| 📊 **Matplotlib** | Training curves and result visualizations |
| 🎨 **Seaborn** | Statistical plots and heatmaps |
| 🤖 **Scikit-learn** | Preprocessing, train-test split, scaling, and evaluation |
| 🧠 **TensorFlow** | Deep learning model development |
| ⚙️ **Keras** | ANN architecture, training, and optimization |
| 📓 **Jupyter Notebook** | Interactive experimentation and documentation |

---

## 📂 Dataset Information

📊 This project uses the **Adult Census Income Dataset** (`adult.csv`).

### 📋 Dataset Summary

| 🔹 Property | 📌 Details |
|:---|:---|
| 📁 Dataset File | `adult.csv` |
| 📊 Original Observations | 48,842 |
| 📑 Original Columns | 15 |
| 🧹 Rows After Missing Value Removal | 45,222 |
| 🗑️ Columns After Dropping Redundant Features | 13 |
| 🔠 Features Before One-Hot Encoding | 12 |
| 🔢 Features After One-Hot Encoding | 80 |
| 🎓 Training Samples | 36,177 |
| 🧪 Testing Samples | 9,045 |
| 🎯 Problem Type | Binary Classification |
| 🏷️ Target Column | `income` |

### 🎯 Target Classes

| 🏷️ Class | 📌 Meaning | 🔢 Label |
|:---|:---|:---:|
| 🔵 Low/Equal Income | Income `<=50K` | `0` |
| 🟢 High Income | Income `>50K` | `1` |

### ⚖️ Dataset Distribution

The target variable contains two income categories:

- 🔵 **Class 0 (`<=50K`)** — Income less than or equal to $50,000.
- 🟢 **Class 1 (`>50K`)** — Income greater than $50,000.

📌 **Note:** The dataset is imbalanced, so Precision, Recall, F1-score, and ROC-AUC are important evaluation metrics alongside Accuracy.



### 📊 Class Distribution After Cleaning

| 🏷️ Income Class | 🔢 Records | 📈 Percentage |
|:---|---:|---:|
| 🔵 `<=50K (0)` | 34,014 | 75.22% |
| 🟢 `>50K (1)` | 11,208 | 24.78% |
| **📊 Total** | **45,222** | **100%** |

### ⚖️ Class Imbalance Analysis

📌 The dataset contains more `<=50K` records than `>50K` records.

⚠️ This indicates an **imbalanced classification problem**.

🎯 Therefore, the project gives special attention to:

- 🎯 **Precision (Class 1)** — Correct positive predictions.
- 🔍 **Recall (Class 1)** — Correctly identified high-income individuals.
- ⚖️ **F1-Score (Class 1)** — Balance between Precision and Recall.
- 📈 **ROC-AUC** — Model's ability to distinguish between both classes.

---

### 🔍 Input Features

📊 The notebook uses **12 input features** related to demographic, employment, educational, and financial information.

| 🔢 No. | 🏷️ Feature Name | 📌 Category |
|:---:|:---|:---|
| 1️⃣ | `age` | 👤 Demographic |
| 2️⃣ | `workclass` | 💼 Employment |
| 3️⃣ | `educational-num` | 🎓 Education |
| 4️⃣ | `marital-status` | 👨‍👩‍👧 Personal |
| 5️⃣ | `occupation` | 💼 Employment |
| 6️⃣ | `relationship` | 👨‍👩‍👧 Personal |
| 7️⃣ | `race` | 🌍 Demographic |
| 8️⃣ | `gender` | 👥 Demographic |
| 9️⃣ | `capital-gain` | 💰 Financial |
| 🔟 | `capital-loss` | 💰 Financial |
| 1️⃣1️⃣ | `hours-per-week` | ⏰ Employment |
| 1️⃣2️⃣ | `native-country` | 🌎 Geographic |

### 🗑️ Dropped Features

The following columns are removed during preprocessing:

- ❌ `fnlwgt` — Final sampling weight.
- ❌ `education` — Dropped because `educational-num` is retained.

📌 **Note:** All preprocessing steps follow the implementation in the Jupyter Notebook.




## ⚙️ Project Workflow

The project follows a complete end-to-end Deep Learning workflow:

1. 📥 **Data Loading:** Load the `adult.csv` dataset using Pandas.

2. 🔎 **Data Inspection:** Check dataset shape, columns, data types, and sample records.

3. 🧹 **Missing-Value Handling:** Replace `?` with `NaN` and remove rows containing missing values.

4. 🗑️ **Feature Removal:** Drop unnecessary columns (`fnlwgt` and `education`).

5. 🎯 **Target Encoding:** Convert income categories into binary labels:
   - 🔵 `<=50K` → `0`
   - 🟢 `>50K` → `1`

6. 📊 **Exploratory Data Analysis (EDA):** Explore income distribution, age, working hours, education, and numerical correlations.

7. 🔠 **Categorical Encoding:** Apply One-Hot Encoding using `pd.get_dummies(drop_first=True)`.

8. ✂️ **Train-Test Split:** Split the dataset into 80% training and 20% testing using `random_state=42` and `stratify=y`.

9. 📏 **Feature Scaling:** Standardize five numerical columns using `StandardScaler`, fitting on training data only.

10. 🧠 **Baseline ANN:** Build and train an initial Multi-Layer Perceptron using TensorFlow/Keras.

11. 🧪 **Model Experiments:** Compare different:
    - ⚡ Activation Functions
    - 🏗️ Weight Initializers
    - ⚖️ Loss Functions
    - 🔄 Batch Normalization Techniques
    - 🚀 Optimization Algorithms

12. 📈 **Model Evaluation:** Evaluate models using Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix, and ROC Curves.

13. 💾 **Model Saving:** Save the final trained ANN model in `.keras` format for future predictions.

---

### 🔄 Workflow Summary

```text
📥 Data Loading
      ⬇️
🔎 Data Inspection
      ⬇️
🧹 Data Cleaning
      ⬇️
🎯 Target Encoding
      ⬇️
📊 Exploratory Data Analysis
      ⬇️
🔠 One-Hot Encoding
      ⬇️
✂️ Train-Test Split
      ⬇️
📏 Feature Scaling
      ⬇️
🧠 Baseline ANN Model
      ⬇️
🧪 Model Optimization
      ⬇️
📈 Model Evaluation
      ⬇️
💾 Final Model Saving


---
```
## 🧠 ANN Architecture

🤖 A reusable **`build_ann()`** function is developed using TensorFlow/Keras to experiment with different neural network configurations, activation functions, weight initializers, optimizers, and regularization techniques.

### 🏗️ Baseline ANN Architecture

The baseline model uses a Multi-Layer Perceptron (MLP) with two hidden layers.

| 🧩 Layer | ⚙️ Configuration |
|:---|:---|
| 📥 Input Layer | 80 encoded features |
| 🧠 Hidden Layer 1 | Dense — 128 neurons, ReLU |
| 🧠 Hidden Layer 2 | Dense — 64 neurons, ReLU |
| 🎯 Output Layer | Dense — 1 neuron, Sigmoid |
| 🚀 Optimizer | Adam |
| ⚖️ Loss Function | Binary Cross-Entropy |
| 📦 Batch Size | 64 |
| 🔄 Epochs | 50 |

📌 **Baseline Model Parameters:** `18,689`

### 🔗 Baseline Architecture Flow
---

```text
📥 Input Layer (80 Features)
          ⬇️
🧠 Dense Layer (128 Neurons)
          ⬇️
⚡ ReLU Activation
          ⬇️
🧠 Dense Layer (64 Neurons)
          ⬇️
⚡ ReLU Activation
          ⬇️
🎯 Output Layer (1 Neuron)
          ⬇️
🔵 Sigmoid Activation
          ⬇️
📊 Income Prediction (0 / 1)

---







```
## 🔬 Experiments Performed

This project performs multiple experiments to analyze and improve ANN performance by comparing different deep learning configurations.

---

### 1. ⚡ Activation Function Comparison

The notebook trains and compares four activation functions:

| ⚡ Activation Function | 📌 Description |
|:---|:---|
| **ReLU** | `max(0, x)` — Introduces non-linearity and helps reduce the vanishing gradient problem. |
| **Tanh** | Produces outputs between `-1` and `1`. |
| **Sigmoid** | Produces outputs between `0` and `1`. |
| **ELU** | Allows negative outputs for negative inputs. |

🔍 **Additional Investigations:**
- 🧠 ReLU Dead Neuron Detection.
- 📉 Sigmoid Gradient Flow Analysis.

<details>
<summary>🏆 Activation Experiment Result</summary>

- **Best Selected Activation:** Sigmoid
- **Class-1 F1-Score:** `0.6874`

</details>

---

### 2. 🏗️ Weight Initialization Comparison

The notebook evaluates five weight initialization techniques:

| 🏗️ Initializer | 📌 Description |
|:---|:---|
| `glorot_uniform` | Glorot Uniform initialization |
| `glorot_normal` | Glorot Normal initialization |
| `he_uniform` | He Uniform initialization |
| `he_normal` | He Normal initialization |
| `zeros` | Initializes all weights with zero |

🔍 **Experiment Objectives:**
- 📊 Analyze training performance.
- 📉 Study gradient flow.
- ⚠️ Understand the symmetry problem caused by zero initialization.
- 🚀 Compare convergence speed.

<details>
<summary>🏆 Weight Initialization Result</summary>

- **Best Selected Initializer:** `glorot_uniform`
- **Class-1 F1-Score:** `0.6795`

</details>

---

### 3. ⚖️ Loss Function Comparison

Four loss-function approaches are investigated:

| ⚖️ Loss Function | 🎯 Purpose |
|:---|:---|
| **Binary Cross-Entropy (BCE)** | Standard loss for binary classification. |
| **Mean Squared Error (MSE)** | Measures squared prediction errors. |
| **Weighted BCE** | Gives additional importance to the minority class. |
| **Focal Loss** | Focuses more on difficult-to-classify samples. |

🎯 **Main Objective:** Improve the prediction performance of the minority income class (`>50K`).

<details>
<summary>🏆 Loss Function Result</summary>

- **Experiment:** Weighted BCE
- **Class-1 F1-Score:** `0.6749`

</details>

---

### 4. 🔄 Batch Normalization Comparison

The notebook compares ANN models with and without Batch Normalization.

Two different layer arrangements are investigated:

**🔹 Approach 1:**
```text
Dense Layer → ReLU → BatchNormalization
---




```
## 📊 Model Results

### 🧠 Baseline ANN Results

The baseline ANN model was evaluated using the held-out test dataset to measure its classification performance.

| 📈 Evaluation Metric | 🎯 Result |
|:---|---:|
| 🎯 Accuracy | **83.95%** |
| 🔍 Precision (Class 1) | **72.89%** |
| 📌 Recall (Class 1) | **56.11%** |
| ⚖️ F1-Score (Class 1) | **63.41%** |

---
```
### 🏆 Selected Experiment Results

The following table summarizes the best recorded results from individual optimization experiments.

| 🔬 Experiment | 🏆 Best Recorded Result |
|:---|:---|
| ⚡ Best Activation — Sigmoid | Class-1 F1: **0.6874** |
| 🏗️ Best Initializer — Glorot Uniform | Class-1 F1: **0.6795** |
| ⚖️ Weighted BCE | Class-1 F1: **0.6749** |
| 🔄 Batch Normalization Model | Class-1 F1: **0.6528** |
| 🚀 Optimizer — SGD | Class-1 F1: **0.6741** |
| 📈 Best Activation — ROC-AUC | **0.9107** |

---
```
### 📌 Performance Analysis

- 🎯 **Accuracy:** Measures the overall percentage of correct predictions.
- 🔍 **Precision:** Measures how many predicted high-income individuals actually belong to Class 1.
- 📌 **Recall:** Measures how many actual high-income individuals are correctly identified.
- ⚖️ **F1-Score:** Balances Precision and Recall.
- 📈 **ROC-AUC:** Measures the model's ability to distinguish between the two income classes.
  ---
```
### ⚠️ Important Notes

📌 These values come from the corresponding experiment outputs in the notebook.

- Individual experiment results are not all measurements of the same final model.
- 🧠 The baseline results represent the initial ANN performance.
- 🔬 Selected experiment results represent individual optimization experiments.
- 🏆 The final combined-model metric table should be used when reporting the final model's complete test performance.

---
```
## 📈 Visualizations

📊 The notebook includes various data analysis plots, training visualizations, and model performance comparisons to understand ANN behavior and evaluate prediction results.
---
```
### 🔍 Exploratory Data Analysis (EDA)

- 📊 Income Class Distribution
- 👥 Age Distribution by Income
- ⏰ Working Hours by Income
- 🎓 Education Level vs Income
- 🔥 Numerical Feature Correlation Heatmap
---
```
### 🧠 ANN Training Visualizations

- 📉 Baseline ANN Training & Validation Curves
- ⚡ Activation Function Comparison
- ☠️ ReLU Dead-Neuron Activation Analysis
- 📊 Sigmoid Gradient-Flow Analysis
- 🏗️ Weight Initialization Comparison
- ⚖️ Loss Function Comparison
- 🔄 Batch Normalization Comparison
- 📈 Batch Normalization Gamma & Beta Analysis
- 🚀 Optimizer Comparison
- 🎚️ Learning-Rate Sensitivity Analysis
---
```
### 🎯 Model Evaluation Visualizations

- 🔲 Confusion Matrices
- 📈 ROC Curves
- 📊 Model Performance Comparison
- ⚖️ Precision, Recall & F1-Score Analysis

---
```
### 🖼️ Project Screenshots

📸 Screenshots of actual notebook visualizations can be stored in the `screenshots/` directory.
---
**📁 Suggested Folder Structure:**

```text
📂 Adult-Income-Prediction-ANN
│
├── 📂 screenshots
│   ├── 📊 income_distribution.png
│   ├── 🔥 correlation_heatmap.png
│   ├── 📉 training_curves.png
│   ├── ⚡ activation_comparison.png
│   ├── 🏗️ initializer_comparison.png
│   ├── ⚖️ loss_comparison.png
│   ├── 🔄 batch_normalization.png
│   ├── 🚀 optimizer_comparison.png
│   ├── 🔲 confusion_matrix.png
│   └── 📈 roc_curve.png
│
├── 📓 Adult Income Prediction Using ANN.ipynb
├── 📄 adult.csv
├── 💾 final_adult_income_ann.keras
└── 📘 README.md

---

```
## 💻 Installation & Setup

### 📥 Step 1: Clone the Repository
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
---


```
### 📂 Step 2: Navigate to the Project Folder

---
cd Adult-Income-Prediction-Using-ANN


```
### 📦 Step 3: Install Dependencies
---

python -m pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter





```
### 🚀 Step 4: Launch Jupyter Notebook

---
python -m jupyter notebook




### 🧠 Step 5: Run the Notebook




1. 📓 Open `Adult Income Prediction Using ANN.ipynb`.
2. 📊 Keep `adult.csv` in the expected project folder.
3. 🐍 Select the Python environment where all required packages are installed.
4. ▶️ Run all notebook cells from top to bottom.
5. 📈 Review the model experiments, evaluation metrics, and visualizations.



   ## 📦 Requirements

| Library | Purpose |
| ------------------ | ----------------------------- |
| 🧠 TensorFlow / Keras | ANN architecture and model training |
| 🐼 Pandas | Data loading and cleaning |
| 🔢 NumPy | Numerical computation |
| ⚙️ Scikit-learn | Data preprocessing and model evaluation |
| 📊 Matplotlib | Data plotting and visualization |
| 🎨 Seaborn | Statistical data visualization |
| 📓 Jupyter Notebook | Interactive development and execution |



## 💡 Key Learnings

- 📂 Loading, inspecting, and cleaning real-world tabular data.
- 🧹 Handling missing values and preparing categorical features.
- 🔠 Applying One-Hot Encoding and numerical feature scaling.
- 🧠 Building reusable ANN models using TensorFlow/Keras.
- ⚡ Understanding activation functions and gradient behaviour.
- 🏗️ Understanding Glorot, He, and zero initialization techniques.
- ⚖️ Exploring loss functions for imbalanced binary classification.
- 🔄 Understanding Batch Normalization and its placement in ANN.
- 🚀 Comparing different optimizers and learning rates.
- 📊 Evaluating models using class-specific Precision, Recall, F1-score, and ROC-AUC.
- 💾 Saving and reusing a trained Keras model.


## 🚀 Future Improvements

- 🔍 Tune the classification threshold to improve class-1 F1-score and Recall.
- 🔄 Apply cross-validation for more reliable model evaluation.
- 🎯 Perform systematic hyperparameter tuning to optimize ANN performance.
- 🧩 Use SHAP or other explainability techniques to understand feature importance and model predictions.
- 🌐 Develop an interactive income prediction application using Streamlit.
- 📦 Save and reuse the complete preprocessing pipeline along with the trained model.
- ⚖️ Evaluate fairness and potential bias across demographic groups before considering real-world use.


## ⚠️ Disclaimer

This project is intended for **educational and learning purposes only**. Predictions are based on patterns in the supplied dataset and should not be treated as definitive judgments about an individual's earning potential, ability, or worth.

The model may reflect biases present in the training data. It should not be used for real-world or consequential decisions without proper validation, fairness assessment, and human oversight.


## 🏁 Conclusion

This project demonstrates an end-to-end **Adult Income Prediction workflow using Artificial Neural Networks (ANN)**. It covers data cleaning, Exploratory Data Analysis (EDA), feature encoding, feature scaling, ANN model development, and multiple optimization experiments.

The baseline ANN achieved **83.95% test accuracy** with a class-1 F1-score of **0.6341**. Different experiments were conducted to compare activation functions, weight initializers, loss functions, Batch Normalization, optimizers, and learning rates.

The recorded experiments identified **Sigmoid** as the best activation configuration with a class-1 F1-score of **0.6874**, while **Glorot Uniform** achieved the best initializer result with a class-1 F1-score of **0.6795**.

Overall, this project strengthened practical understanding of **tabular data preprocessing, deep learning, class imbalance, neural network optimization, and model evaluation**.

## 👨‍💻 Author

**Rahul Zala**

💻 *Python Developer | Data Analytics | Machine Learning | Deep Learning*

📌 Passionate about data analysis, machine learning, and building practical deep learning projects.

---

<p align="center">

⭐ If you find this project useful, please consider giving the repository a star!

🤝 Contributions, feedback, and suggestions are always welcome.

</p>
