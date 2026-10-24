# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

This project is a **Heart Disease Prediction System** developed using Python and Machine Learning. It analyzes user-provided health information and predicts whether the person may be at risk of heart disease.

The project includes a Jupyter Notebook for data analysis and model development, along with a Streamlit web application that allows users to enter their health details and view a prediction.

## 🎯 Objectives

- Analyze heart disease data using Python.
- Perform data cleaning and exploratory data analysis (EDA).
- Prepare categorical and numerical features for machine learning.
- Train and compare multiple classification algorithms.
- Build an interactive web application using Streamlit.
- Display heart disease risk predictions based on user inputs.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Web Application:** Streamlit
- **Model Serialization:** Joblib
- **Development Environment:** Jupyter Notebook, VS Code

## 🤖 Machine Learning Algorithms

The notebook explores the following classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)

The Streamlit application loads a saved Logistic Regression model to generate predictions.

## 📊 Features

- Interactive input form for health-related information.
- Age, sex, chest pain type, resting blood pressure, and cholesterol inputs.
- Fasting blood sugar, resting ECG, maximum heart rate, exercise-induced angina, oldpeak, and ST slope inputs.
- Data preprocessing and feature alignment before prediction.
- Prediction results displayed in the Streamlit interface.
- Simple and user-friendly interface.

## 📁 Project Structure

```text
Heart-Disease-Prediction/
│
├── app.py
├── heart_disease_prdiction.ipynb
├── heart.csv
├── LogisticRegression_heart.pkl
├── scaler.pkl
├── columns.pkl
├── requirements.txt
└── README.md
```

**Note:** The CSV dataset and three `.pkl` files must be available for the project to run as configured. Add these files to your repository if you are permitted to share them.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Heart-Disease-Prediction.git
```

### 2. Open the project folder

```bash
cd Heart-Disease-Prediction
```

### 3. Install the dependencies

```bash
pip install streamlit pandas scikit-learn joblib numpy matplotlib seaborn jupyter
```

### 4. Run the application

```bash
streamlit run app.py
```

The application will open in your browser. Enter the requested details and click **Predict** to see the model's output.

## 📓 Jupyter Notebook

Open `heart_disease_prdiction.ipynb` in Jupyter Notebook to explore the dataset, perform exploratory data analysis, preprocess the data, and experiment with classification models.

Ensure that `heart.csv` is in the appropriate working directory before running the notebook.

## 📈 Future Improvements

- Display model evaluation metrics such as accuracy, precision, recall, and F1-score.
- Improve input validation and error handling.
- Enhance the user interface with visual summaries.
- Evaluate model performance on independent test data.
- Deploy the application online for demonstration purposes.

## ⚠️ Disclaimer

This project is intended for educational and machine learning demonstration purposes only. Predictions are not medical diagnoses and must not be used to make medical decisions. Consult a qualified healthcare professional for medical advice.

## 👩‍💻 Author

**Arya Singh**

Aspiring Data Analyst | Machine Learning Enthusiast

GitHub: [YOUR-GITHUB-PROFILE](https://github.com/YOUR-USERNAME)

---

⭐ If you find this project interesting, feel free to star the repository!
