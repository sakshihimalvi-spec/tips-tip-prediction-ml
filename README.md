# Tips Prediction Streamlit App

## Project Overview
This project is a Machine Learning application that predicts the tip amount in a restaurant based on different features such as total bill, number of people, gender, smoking status, day, and time. The project includes exploratory data analysis (EDA), model training, and deployment using a Streamlit web application.

## Features
- Exploratory Data Analysis on the Tips dataset
- Data preprocessing and feature engineering
- Machine Learning model training using Scikit-learn
- Model evaluation using performance metrics
- Model saved using Pickle
- Interactive web application using Streamlit for predictions

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
- Pickle

## Project Structure
```
tips-prediction-streamlit-app/
│
├── eda.ipynb          # Data analysis and model training
├── app.py             # Streamlit web application
├── tips_model.pkl     # Saved machine learning model
├── requirements.txt   # Project dependencies
└── README.md          # Project documentation
```

## Dataset Features
The model predicts the tip amount using the following inputs:

- Total Bill
- Size (number of people)
- Sex
- Smoker
- Day
- Time

## Model
The machine learning model is trained using the Scikit-learn library. The dataset is preprocessed using encoding and scaling techniques before training the model.

## How to Run the Project

### 1 Install Dependencies
```bash
pip install -r requirements.txt
```

### 2 Run the Streamlit App
```bash
streamlit run app.py
```

### 3 Open in Browser
After running the command, Streamlit will generate a local URL such as:

```
http://localhost:8501
```

Open it in your browser to use the application.

## Example Prediction
The user enters:
- Total Bill
- Size
- Sex
- Smoker
- Day
- Time

The application will then predict the expected **Tip Amount**.

## Learning Outcomes
Through this project, the following concepts are demonstrated:

- Exploratory Data Analysis (EDA)
- Feature preprocessing
- Machine Learning model training
- Model evaluation
- Model serialization using Pickle
- Deployment using Streamlit

## Future Improvements
- Add more advanced regression models
- Improve feature engineering
- Deploy the application online
- Add more visualization in the web interface

## Author
Developed as a Machine Learning and Data Analysis project using Python and Streamlit.
Himlavi SKH
