# Healthcare-Premium-Prediction
Health Insurance Prediction Project
# 🏥 Healthcare Premium Prediction

Project link : https://nigaralizada9-healthcare-premium-prediction-main-l0njgr.streamlit.app/


This project represents how I approach machine learning beyond notebooks — focusing on **building usable, interactive, and deployment-ready systems**.

---

## 🚀 Project Summary

This is an end-to-end **ML-powered Streamlit application** that predicts health insurance premiums based on user inputs.

Unlike typical ML projects, this one doesn’t stop at model training — it delivers a **working user interface + inference pipeline**, which is much closer to real-world applications.

---

## 💡 What makes this project stand out


In this project, I focused on:

* ✅ Turning the model into a **usable application (Streamlit UI)**
* ✅ Designing a **clean inference pipeline**
* ✅ Ensuring **training–inference consistency via artifacts**
* ✅ Writing modular, maintainable code

---

## 🖥️ Application Layer (Streamlit)

The app is built using **Streamlit**, allowing users to interactively input their data.

### Features:

* Dropdown-based categorical inputs
* Structured user form (gender, BMI, smoking, etc.)
* Real-time prediction output

, not just a script.

---

## 🏗️ System Design

```
User Input (Streamlit UI)
        ↓
Preprocessing (encoders, scalers)
        ↓
Model (trained artifact)
        ↓
Prediction Output (premium)
```

---

## 🗂️ Project Structure

```
Healthcare-Premium-Prediction/
│
├── artifacts/                # Model + preprocessing objects
├── main.py                  # Streamlit app (UI + input handling)
├── prediction_helper.py     # Core ML logic (load → preprocess → predict)
├── README.md
├── LICENSE
├── .gitignore
│
└── requirements.txt
```

---

## ⚙️ How it works

1. User inputs data through Streamlit UI
2. `main.py` collects and formats inputs
3. `prediction_helper.py`:

   * loads artifacts
   * preprocesses inputs
   * runs prediction
4. Predicted premium is displayed instantly

---

## 📦 Artifact-Driven Design

Artifacts stored in `/artifacts` ensure consistency:

* trained model
* encoders
* scalers

This avoids one of the biggest real-world ML issues:

> ❗ Training vs inference mismatch

---

## 📊 Inputs & Output

### Inputs

* Age
* Gender
* BMI category
* Smoking status
* Employment status
* Medical history
* Region
* Insurance plan

### Output

* Predicted health insurance premium

---

## 🛠️ Running the App

```bash
cd Healthcare-Premium-Prediction
streamlit run main.py
```

---

## ⚠️ Real-World Awareness

While this is a simplified system, I designed it with awareness of:

* bias in pricing models
* fairness considerations
* need for explainability
* handling sensitive health data
* model monitoring and drift

---



---

## 🧑‍💻 What this project shows about me

This project reflects how I think as a data scientist:

* I build **end-to-end solutions**, not just models
* I care about **user experience + ML correctness**
* I understand that **real ML = pipelines + systems + usability**


---

Thanks for taking a look 🙏

