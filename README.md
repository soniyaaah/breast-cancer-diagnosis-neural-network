# breast-cancer-diagnosis-neural-network
Neural network–based classification model for breast cancer diagnosis using the Breast Cancer Wisconsin dataset, built with TensorFlow and Keras.
# Breast Cancer Classification using Neural Network

This project implements a **Neural Network-based classification model** to predict whether a breast tumor is **Malignant** or **Benign** using the **Breast Cancer Wisconsin dataset**.

The model is built using **TensorFlow and Keras** and demonstrates a complete machine learning workflow from data preprocessing to prediction.

---

## 📊 Dataset
- Source: `sklearn.datasets.load_breast_cancer`
- Total Features: 30 numerical features
- Target Variable:
  - `0` → Malignant
  - `1` → Benign

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading & Exploration
- Loaded dataset from Scikit-learn
- Converted data into a Pandas DataFrame
- Performed basic exploratory analysis and target distribution check

### 2️⃣ Data Preprocessing
- Separated features and target variable
- Split data into training and testing sets
- Standardized features using `StandardScaler`

### 3️⃣ Model Architecture
- Input Layer: 30 features
- Hidden Layer: Dense layer with ReLU activation
- Output Layer: 2 neurons with Sigmoid activation

### 4️⃣ Model Training
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 10
- Validation Split: 10%

### 5️⃣ Model Evaluation
- Evaluated model performance on test data
- Visualized training and validation accuracy and loss

### 6️⃣ Prediction
- Tested the model on a new input sample
- Classified tumor as **Malignant** or **Benign**

---

## 📈 Results
- Achieved high classification accuracy on test data
- Model successfully distinguishes between malignant and benign tumors

---

## ▶️ How to Run the Project
```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```
```
python breast_cancer_nn.py
```
