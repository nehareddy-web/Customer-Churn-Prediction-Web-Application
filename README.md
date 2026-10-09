<!-- ============================================================
  HORROR README - Customer Churn Prediction Web Application
  Paste into README.md of this repo. Search "EDIT" for things to check.
============================================================= -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,40:3B0000,100:8B0000&height=260&section=header&text=THE%20VANISHING&fontColor=E50914&fontSize=70&fontAlignY=38&animation=blinking&desc=Customer%20Churn%20Prediction%20Web%20Application&descAlignY=62&descSize=22&descColor=ffffff" width="100%" alt="The Vanishing"/>

<img src="https://readme-typing-svg.demolab.com?font=Creepster&size=28&duration=2800&pause=900&color=E50914&center=true&vCenter=true&width=800&height=60&lines=Customers+are+disappearing...;Nobody+noticed+the+warning+signs.;Except+the+model.;Predict+who+leaves.+Before+they+leave." alt="Typing SVG"/>

<br/>

![Rating](https://img.shields.io/badge/RATED-TV--MA-E50914?style=for-the-badge)
![Genre](https://img.shields.io/badge/GENRE-DATA_HORROR-000000?style=for-the-badge&labelColor=000000&color=8B0000)
![Accuracy](https://img.shields.io/badge/ACCURACY-84%25-8B0000?style=for-the-badge&labelColor=000000)
![ROC-AUC](https://img.shields.io/badge/ROC--AUC-0.89-E50914?style=for-the-badge&labelColor=000000)

![Python](https://img.shields.io/badge/Python-0A0A0A?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-8B0000?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0A0A0A?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-8B0000?style=for-the-badge&logo=streamlit&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-0A0A0A?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   ⚠  VIEWER DISCRETION ADVISED  ⚠                            ║
║                                                              ║
║   This project contains: disappearing customers, hidden      ║
║   warning signs, and predictions that may cause sudden       ║
║   retention strategies.                                      ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 🕯️ THE PLOT

> *Every month, some customers simply stop answering. They cancel, they leave, they vanish. The signs were always there, buried in the data.*

An **end-to-end Machine Learning project** that predicts whether a telecom customer is likely to **churn** (leave the service) from their demographics, service usage and billing data.

It covers data preprocessing, EDA, model training, evaluation, and **deployment as a Streamlit web app** for real-time predictions.

---

## 🩸 THE EVIDENCE

| 🔪 Clue | 🩸 Finding |
|:--|:--|
| 🗄️ **Records investigated** | **7,500+** telecom customers |
| 🤖 **Models interrogated** | Logistic Regression, XGBoost |
| 🎯 **Accuracy** | **84%** after hyperparameter tuning |
| 📈 **ROC-AUC** | **0.89** |
| 🌐 **Deployment** | Streamlit app for real-time predictions |

---

## 💀 WARNING SIGNS: *TOP CHURN DRIVERS*

The customers who vanished all had something in common:

```
 🔴  CONTRACT TYPE        →  the type of contract strongly shapes who leaves
 🔴  TENURE > 12 MONTHS   →  tenure is a key signal in who stays or goes
 🔴  MONTHLY CHARGES      →  charges above ₹800 are a red flag
```
<!-- EDIT: confirm the direction of each driver (e.g., month-to-month contracts churn more) and reword if you want it more specific -->

---

## 🔍 THE INVESTIGATION: *PIPELINE*

```
   📥 RAW DATA
       │
       ▼
   🧹 PREPROCESSING      clean, encode, scale
       │
       ▼
   🔎 EDA                find patterns and churn drivers
       │
       ▼
   🧪 MODEL TRAINING     Logistic Regression, XGBoost
       │
       ▼
   📊 EVALUATION         Accuracy 84%, ROC-AUC 0.89
       │
       ▼
   🌐 STREAMLIT APP      real-time churn prediction
```

---

## 🖥️ SYSTEM LOG

```
$ ./predict --customer=C-0427
[ OK ]  Loading trained model...
[ OK ]  Reading customer profile...
[WARN]  High monthly charges detected.
[WARN]  Contract type is a known risk factor.
[ !! ]  Churn probability: HIGH
[DONE]  Recommended action: retention offer.

$ status
> This customer has not vanished yet.
```
<!-- This log is just storytelling to match the theme -->

---

## 🛠️ THE ARSENAL

| 🧰 Category | ⚔️ Tools |
|:--|:--|
| Language | Python |
| Data & analysis | Pandas, NumPy, SQL |
| Visualization | Matplotlib, Seaborn |
| Modelling | Scikit-learn, XGBoost |
| Deployment | Streamlit |
<!-- EDIT: remove Matplotlib/Seaborn/NumPy if you didn't use them -->

---

## 🚪 ENTER IF YOU DARE: *RUN IT LOCALLY*

```bash
# 1. Clone the repository
git clone https://github.com/nehareddy-web/Customer-Churn-Prediction-Web-Application.git
cd Customer-Churn-Prediction-Web-Application

# 2. Install the dependencies
pip install -r requirements.txt

# 3. Summon the app
streamlit run app.py
```
<!-- EDIT: change app.py and requirements.txt if your files have different names -->

---

## 🔮 THE SEQUEL

- 🔴 Connect the app to a live SQL database
- 🔴 Add feature-importance charts inside the app
- 🔴 Try more models and compare against XGBoost
<!-- EDIT: keep only the ones you actually plan to do -->

---

<div align="center">

### 🩸 THE STORY ISN'T OVER.

*The customers who left can't be saved. The ones who haven't left yet still can.*

[![▶ MORE FROM THE AUTHOR](https://img.shields.io/badge/▶_MORE_CASE_FILES-GitHub_Profile-E50914?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nehareddy-web)
[![CONNECT](https://img.shields.io/badge/💀_CONNECT-LinkedIn-8B0000?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nehareddy11)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B0000,50:3B0000,100:000000&height=120&section=footer&text=Don't%20look%20behind%20you...&fontSize=20&fontColor=ffffff&fontAlignY=68&animation=blinking" width="100%" alt="footer"/>

</div>
