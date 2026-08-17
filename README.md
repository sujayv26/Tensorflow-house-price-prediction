# TensorFlow-House-Price-Prediction

MLOPS Assignment

# 🏠 House Price Prediction using TensorFlow

## 📌 Project Overview

This project implements a **Neural Network Regression model using TensorFlow and Keras** to predict **house prices** based on house-related features such as area, number of bedrooms, bathrooms, stories, and age.

The project demonstrates the complete machine learning workflow, including data preprocessing, feature scaling, model development, training, evaluation, prediction, and visualization using Python.

---

## 🎯 Objective

To build a TensorFlow-based regression model capable of predicting house prices using various features of houses.

---

## 📂 Dataset

**Dataset Name:** House Price Prediction Dataset

The dataset contains **300 records** with **6 columns** related to house characteristics.

### Features

* Area
* Bedrooms
* Bathrooms
* Stories
* Age
* Price (Target Variable)

### Dataset Details

* Total Records: **300**
* Total Columns: **6**
* Training Samples: **240**
* Testing Samples: **60**
* Missing Values: **None**

The features **Area, Bedrooms, Bathrooms, Stories, and Age** are used as input variables, while **Price** is used as the target variable.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* TensorFlow
* Keras
* Jupyter Notebook

---

## 📁 Project Structure

```text
TensorFlow-House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── house_prices.csv
├── README.md
└── report/
    └── Ex3_24BTRAO041_SujayV.pdf
```

---

## ⚙️ Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Check for missing values
5. Select input features and target variable
6. Split the dataset into training and testing sets
7. Scale input features using StandardScaler
8. Scale the target variable
9. Build the TensorFlow Keras neural network
10. Compile the regression model
11. Train the model
12. Evaluate the model
13. Generate house price predictions
14. Convert predictions back to the original price scale
15. Compare actual and predicted prices
16. Visualize training and validation loss
17. Visualize actual vs predicted prices

---

## 🧠 Model Architecture

The regression model was developed using **TensorFlow and Keras**.

### Neural Network Structure

```text
Input Layer
     ↓
Dense Layer – 64 Neurons
     ↓
Dense Layer – 32 Neurons
     ↓
Output Layer – 1 Neuron
```

### Model Configuration

* Optimizer: **Adam**
* Learning Rate: **0.001**
* Loss Function: **Mean Squared Error (MSE)**
* Evaluation Metric: **Mean Absolute Error (MAE)**
* Epochs: **200**
* Batch Size: **16**
* Validation Split: **20%**
* Trainable Parameters: **2,497**

---

## 📊 Model Evaluation

The trained model was evaluated using standard regression metrics.

| Metric                         |                Value |
| ------------------------------ | -------------------: |
| Mean Absolute Error (MAE)      |        **45,094.16** |
| Mean Squared Error (MSE)       | **3,167,534,592.00** |
| Root Mean Squared Error (RMSE) |        **56,280.85** |
| R² Score                       |           **0.8842** |

The model achieved an **R² score of 0.8842**, indicating that the model explains approximately **88.42% of the variation in house prices** on the test dataset.

---

## 📈 Visualizations

The project includes:

* Training vs Validation Loss Plot
* Actual vs Predicted House Prices Table
* Actual vs Predicted House Prices Scatter Plot

These visualizations help analyze the model's learning behavior and compare predicted house prices with actual house prices.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/sujayv26/TensorFlow-House-Price-Prediction.git
```

### 2. Navigate to the project

```bash
cd TensorFlow-House-Price-Prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

```bash
jupyter notebook
```

Open **House_Price_Prediction.ipynb** and execute all cells.

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
scikit-learn
tensorflow
jupyter
```

---

## 📌 Results

* Successfully developed a TensorFlow-based neural network regression model.
* Successfully predicted house prices using five input features.
* Achieved an **R² score of 0.8842**.
* Obtained a **Mean Absolute Error of 45,094.16**.
* Obtained a **Root Mean Squared Error of 56,280.85**.
* Demonstrated an end-to-end machine learning workflow for regression.
* Visualized training performance and actual versus predicted house prices.

---

## 📚 Learning Outcomes

* Data Loading and Exploration
* Data Preprocessing
* Feature Scaling
* Target Scaling
* Train-Test Splitting
* TensorFlow and Keras
* Neural Network Regression
* Model Training
* Model Evaluation
* Regression Metrics
* Data Visualization
* House Price Prediction
* GitHub Project Management

---

## 👨‍💻 Author

**Sujay V**

B.Tech CSE (AI Driven DevOps)

Jain University

---

## 📄 License

This project was developed for educational purposes as part of a Machine Learning Operations laboratory assignment.
