# 🏥 Multiple Disease Prediction System

This is an AI-powered health prediction web application built with **Streamlit**.
It allows users to check the risk of **Kidney Disease**, **Liver Disease**, and **Parkinson’s Disease** by entering their medical parameters.

---

## ✅ Features

* Kidney Disease Prediction 💧
* Liver Disease Prediction 🍂
* Parkinson’s Disease Prediction 🧠
* Sidebar navigation with a clean and interactive UI
* Customized CSS styling for a professional look
* Multiple disease predictions in a single platform

---

## 🛠️ Tech Stack

* **Python 3.8+**
* **Streamlit** – Web UI
* **Pandas & NumPy** – Data handling
* **Scikit-learn** – Model training and prediction
* **Pickle** – Loading pre-trained ML models

---

## 📂 Project Structure

```
Multiple_Disease_Prediction/
│
├── kidney.pkl                 # Pre-trained kidney disease model
├── liver.pkl                  # Pre-trained liver disease model
├── parkinsons_model.pkl       # Pre-trained Parkinson’s disease model
├── app.py                     # Main Streamlit application
└── README.md                  # Documentation file
```

---

## 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/multiple-disease-prediction.git
cd multiple-disease-prediction
```

### 2️⃣ Install Dependencies

Make sure you have Python installed. Then run:

```bash
pip install -r requirements.txt
```

**Example `requirements.txt`:**

```
streamlit
pandas
numpy
scikit-learn
streamlit-option-menu
```

### 3️⃣ Place Model Files

Put your trained models (`kidney.pkl`, `liver.pkl`, `parkinsons_model.pkl`) inside the project folder, or update the paths in `app.py`.

### 4️⃣ Run the Application

```bash
streamlit run app.py
```

The app will launch in your browser at [http://localhost:8501/](http://localhost:8501/) 🎉

---

## 🖼️ Screenshots

### Home Page

* Overview of application and usage instructions

### Prediction Pages

* Separate input forms for Kidney, Liver, and Parkinson’s Disease

---

## 📋 Example Predictions

**Liver Disease Prediction 🍂**

* **Input:** Age, Gender, Bilirubin, Enzymes, Protein levels
* **Output:** Risk status + Health advice

**Kidney Disease Prediction 💧**

* **Input:** Blood Pressure, Sugar, Albumin, Serum Creatinine, etc.
* **Output:** Risk status + Health advice

**Parkinson’s Disease Prediction 🧠**

* **Input:** Acoustic features from voice measurement
* **Output:** Risk status + Health advice

---

## 🤝 Contribution

1. Fork the repo
2. Create a new branch (`feature-xyz`)
3. Commit your changes
4. Create a Pull Request

---

## ⚠️ Disclaimer

This application is **not a medical diagnostic tool**.
It only provides AI-based risk predictions.
Always consult a licensed medical professional for accurate diagnosis and treatment.
