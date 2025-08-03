# 💳 Fraud Detection on Bank Payments

> 🎓 **Minor Project – Academic Submission**  
> This project was developed as part of my academic curriculum to demonstrate practical understanding of Machine Learning and Web Development concepts.

An intelligent web application to detect **fraudulent** vs **benign** bank transactions using machine learning.

> 🔍 Built with Python, Flask, Random Forest, and a user-friendly HTML interface.

---

## 🚀 Features

- 📤 Upload CSV datasets for batch fraud analysis  
- 🧠 Predict single transactions manually using form input  
- 📈 Displays model performance  
- 🎨 Responsive frontend built using HTML templates  
- 🔐 Trained ML model saved and used via `fraud.pkl`

---

## 🧠 ML Model Details

- **Algorithm:** Random Forest Classifier  
- **Train Accuracy:** 99%  
- **Test Accuracy:** 99%  
- Model file: `fraud.pkl`  
*(Details from [Accuracy.txt](Accuracy.txt))*

---

## 📂 Project Structure

fraud-detection/
├── app.py # Main Flask server
├── fraud.pkl # Trained ML model
├── upload.csv # Sample input dataset
├── requirements.txt # Python dependencies
├── Accuracy.txt # Accuracy metrics
├── README.md # Project overview
└── templates/ # HTML templates (Flask frontend)
├── first.html
├── login.html
├── upload.html
├── preview.html
├── prediction.html
├── performance.html
└── chart.html

---

## ⚙️ Installation

### 🔧 Prerequisites
- Python **3.8** or **3.9.12**
- `pip` package manager

### 🛠️ Setup

```bash
# 1. Clone this repository
git clone https://github.com/your-username/fraud-detection-bank-payments.git
cd fraud-detection-bank-payments

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask app
python app.py
🌐 Access the app
Open your browser and go to:
http://127.0.0.1:5000/

🧪 Try it with dataset.csv
Use the provided dataset.csv file to test the upload and prediction features.

📌 Pages in the Web App
Route	Description
/	Root/home route
/first	First landing page
/login	Login page
/upload	Upload dataset page
/preview	Display dataset
/prediction	Manual input form
/predict	Shows prediction result
/performance	Model performance display
/chart	Placeholder for future chart visualization

🧾 Requirements

pandas==1.4.2
numpy==1.21.6
scikit-learn==1.1.3
flask==1.1.2
matplotlib
(


📬 Contact
For questions, suggestions, or collaborations, feel free to:

Open an Issue

Fork this project

Connect via GitHub
