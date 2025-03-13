
# Personal Fitness Tracker

1. Overview  
The **Personal Fitness Tracker** is a Streamlit-based web application that predicts the number of kilocalories burned during exercise based on user input parameters such as age, BMI, heart rate, body temperature, and duration of the exercise.

2. Features  
- Interactive UI using Streamlit  
- Predicts calories burned based on user inputs  
- Uses **Random Forest Regression** for predictions  
- Provides a comparison of user stats with others  
- Displays similar calorie burn results from the dataset  

3. Installation 
### **1. Clone the Repository**  
```bash
git clone https://github.com/your-username/fitness-tracker.git
cd fitness-tracker
```

### **2. Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3. Run the App**  
```bash
streamlit run app.py
```

## **Project Structure**  
```
fitness-tracker/
│-- app.py                 # Streamlit application file  
│-- calories.csv           # Dataset containing calories burned  
│-- exercise.csv           # Dataset containing user exercise details  
│-- fitness_tracker.ipynb  # Jupyter Notebook for model training  
│-- requirements.txt       # Dependencies list  
│-- README.md              # Project documentation  
```

## **Technologies Used**  
- **Python**  
- **Streamlit** (for the web app)  
- **Scikit-Learn** (for machine learning)  
- **Pandas & NumPy** (for data handling)  
- **Matplotlib & Seaborn** (for visualization)  

## **How It Works**  
1. The user enters personal fitness parameters in the sidebar.  
2. The app uses a trained **Random Forest Regressor** model to predict the calories burned.  
3. It also compares the user's values to others in the dataset.  
4. Similar calorie-burning cases are displayed.  

## **Dataset**  
- `calories.csv` - Contains the actual calories burned.  
- `exercise.csv` - Contains information like age, BMI, duration, heart rate, and body temperature.  

## **Future Improvements**  
- Add more exercise types to improve prediction accuracy.  
- Implement user authentication for saving historical data.  
- Support additional machine learning models for better accuracy.  

## **License**  
This project is licensed under the MIT License.  
