# AGRICULTURAL CROP RECOMMENDATION SYSTEM

## Project Description

This machine learning project predicts the most suitable crop based on soil nutrients and environmental conditions.

The system takes input values such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall, and recommends the best crop to grow for those conditions.

Features:
- Accepts soil and environmental parameters as input
- Uses trained machine learning model for prediction
- Recommends suitable crop
- Simple user interface for input and output


## Technologies Used

- Python
- Flask
- NumPy
- Pandas
- Scikit-learn
- HTML
- CSS


## Machine Learning Algorithm

The model used in this project:

- Random Forest Classifier


## Dataset

Dataset used:

Crop_recommendation.csv

Input Features:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

Output:

- Crop label (Recommended Crop)


## Project Structure

project/
│

├── app.py

├── model.pkl

├── Crop_recommendation.csv

├── requirements.txt

├── templates/

│            └── index.html

├── static/
  
│            └── style.css

├── README.md



## How to Run the Project

1. Clone the repository:
git clone <repository-link>

2. Navigate to project folder:
cd project-folder

3. Install dependencies:
pip install -r requirements.txt

4. Run the application:
python app.py

5. Open browser and go to:
http://127.0.0.1:5000/


## Input Parameters

The system accepts the following inputs:

- Nitrogen
- Phosphorus
- Potassium
- Temperature
- Humidity
- pH
- Rainfall


## Output

The system predicts and displays the most suitable crop based on the given input values.
