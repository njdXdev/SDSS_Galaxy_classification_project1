# 🌌 SDSS Galaxy Classification (Machine Learning Project)

An end-to-end Machine Learning project to classify galaxies from the **Sloan Digital Sky Survey (SDSS)** into **Starforming** or **Starburst** subclasses.
The project includes complete ML workflow and a Flask-based web interface for real-time prediction.

---

## 🚀 Features

* Data cleaning & preprocessing
* Feature selection using **SelectKBest**
* Class balancing with **SMOTE**
* Training with **Random Forest**, **Logistic Regression**, and **Decision Tree**
* Input scaling using **StandardScaler**
* Flask web app with a clean, styled UI
* Real-time prediction integrated with the trained model

---

## 🧠 Model Used

**RandomForestClassifier** (best-performing model)

---

## 📦 Large Files (Hosted Externally)

Due to GitHub file size limits, the trained model and dataset are available here:

* **Trained Model (RandomForest2.pkl):** [Google Drive Link](https://drive.google.com/file/d/1JJWYnkX9p3gxc1qQyD7fBYS6P23D5RAD/view?usp=sharing)
* **Dataset (SDSS CSV):** [Google Drive Link](https://docs.google.com/spreadsheets/d/1InUAJG-67KAOrXS2FVwodAdnFIVXphHrK8LR_TGy24o/edit?usp=sharing)

---

## ▶️ Running the App Locally

1. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
2. Download **RandomForest2.pkl** from Google Drive and place it in the project folder.
3. Run the Flask app:

   ```
   python app.py
   ```
4. Open in browser:
   **[http://127.0.0.1:5000/](http://127.0.0.1:5000/)**

---

## 👤 Author

**Muhammed Najeed P**
