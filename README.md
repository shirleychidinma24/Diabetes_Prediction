# Diabetes Prediction App

This project is a **Diabetes Prediction Web Application** built using a Machine Learning model trained on a healthcare dataset. Users can input key health parameters (e.g. Glucose, BMI, Age, Pregnancies), and the app predicts their likelihood of having diabetes.

The solution consists of:
- A **Jupyter Notebook** for data exploration, model training & evaluation.
- [You can see ml_diabetes jupyter notebook](https://github.com/shirleychidinma24/Diabetes_Prediction/blob/main/Ml_Project.ipynb)
- A data exploration visualization
- ![Data exploration visualization Screenshot](https://github.com/shirleychidinma24/Diabetes_Prediction/blob/main/Data%20exploration%20visualization.png)

- A **Streamlit** app for a user-friendly interface to make predictions.
![App Screenshot](https://github.com/shirleychidinma24/Diabetes_Prediction/blob/main/Diabetes%20prediction%20screenshot.png)

## Key Features
- Loads a pre-trained Diabetes model and scaler.
- Scales user inputs and provides real-time diabetes risk predictions.
- Displays the predicted outcome with confidence level.
- Interactive interface powered by Streamlit.

- ## Dataset
- This project is trained on the **Pima Indians Diabetes Dataset** containing features such as:
- Glucose
- BMI
- Age
- Pregnancies
- Insulin
- SkinThickness
- DiabetesPredigreeFunction
- BloodPressure

You can obtain the dataset from [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database?select=diabetes.csv)


## Feature Selection Technique
- We can use correlation matrix to pick the most important feature
- Correlation Matrix measure the linear relationship between the target and the feature
- Helps visualize which features are strongly correlated with outcome

- ## Model Development
1. *Preprocessing*: Features were scaled using StandardScaler.
2. *Model Training*: A LogisticRegression model was trained and saved with joblib.
3. *Evaluation*:
   - Accuracy: ~80%
   - Confusion Matrix and metrics were calculated
