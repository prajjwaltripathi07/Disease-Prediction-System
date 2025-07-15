cd# Disease Prediction System

A web-based application that predicts diseases based on user-input symptoms and provides relevant information such as disease description, precautions, medications, recommended diets, and workouts.

## Features
- Predicts disease from symptoms using a trained machine learning model (SVC).
- Provides disease description, precautions, medications, diet, and workout recommendations.
- User-friendly web interface built with Flask.
- Multiple pages: Home, About, Contact, Developer, Blog.

## Project Structure
```
main.py                # Flask application
models/svc.pkl         # Trained SVC model
static/img.png         # Static image asset
templates/             # HTML templates for web pages
    index.html
    about.html
    contact.html
    developer.html
    blog.html
datasets/              # Supporting CSV datasets
    description.csv
    diets.csv
    medications.csv
    precautions_df.csv
    Symptom-severity.csv
    symtoms_df.csv
    Training.csv
    workout_df.csv
```

## Setup Instructions
1. **Clone the repository**
   ```powershell
   git clone <repo-url>
   cd Disease-Prediction-System
   ```
2. **Install dependencies**
   ```powershell
   pip install flask numpy pandas
   ```
3. **Run the application**
   ```powershell
   python main.py
   ```
4. **Access the web app**
   Open your browser and go to `http://127.0.0.1:5000/`

## Usage
- Enter symptoms (comma-separated) on the home page and submit.
- The app will predict the most likely disease and display relevant information.

## Datasets
- All supporting datasets are in the `datasets/` folder.
- Model file is in `models/svc.pkl`.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is for educational purposes.

## Example Screenshots
Below are slots for 3 example pictures of the application:

| Screenshot 1 | Screenshot 2 | Screenshot 3 |
|--------------|--------------|--------------|
| ![Screenshot 1](static/img1.png) | ![Screenshot 2](static/img2.png) | ![Screenshot 3](static/img3.png) |

Replace `img1.png`, `img2.png`, and `img3.png` in the `static/` folder with your actual images to display them here.