# 🌿 TripleLens — ESG Risk Analysis Platform

> **Insight. Impact. Integrity.**

A full-stack ESG (Environmental, Social, and Governance) Risk Analysis Platform that helps investors analyze companies and predict investment risk levels using Machine Learning.

<p align="center">
  <img src="https://raw.githubusercontent.com/varshitha201005/esg-risk-platform/main/esg-risk-platform1/esg_logo.png" width="200"/>
</p>

---

## 🚀 Live Demo

🌐 **Web App:** [Click here to open TripleLens](https://esg-risk-platform-q9uc8ktfzwtu3ny6mpeepe.streamlit.app)

📱 **Android APK:** [Download TripleLens v1.0.0](https://github.com/varshitha201005/esg-risk-platform1/releases/download/v1.0.0/TripleLens-v1.0.0.apk)

---

## 📌 Features

### 🔐 Authentication
- User Registration with password strength indicator
- Secure Login with bcrypt encryption
- Persistent user database via Google Sheets

### 📊 Dashboard
- KPI cards with total companies, risk counts and avg ESG score
- Top company spotlight
- Company rankings and score spread
- ESG pillar deep-dive charts
- Risk overview with donut chart
- Sector analysis and breakdown
- Pillar score distributions
- Top 10 safest companies table

### 🔬 Data Preview
- Filtered dataset with search
- Statistical summary
- Column profiler
- Correlation heatmap
- Outlier detection

### 🤖 ML Predictions
- 3 ML models — Random Forest, Logistic Regression, Gradient Boosting
- Model performance cards with cross-validation
- Feature importance analysis
- Single company risk prediction with confidence probabilities
- Pillar contribution donut chart
- Comparison with dataset average
- Batch prediction via CSV upload

### 📈 Model Evaluation
- Performance metrics — Accuracy, Precision, Recall, F1 Score
- Interactive confusion matrix
- All-models radar chart
- Side-by-side model comparison
- Best model leaderboard

### 🏢 Company Insights
- Detailed company profile card with dataset rank
- ESG radar chart vs dataset average
- 6-month score history trend
- Investment recommendation
- Pillar score breakdown
- Peer comparison within same risk tier
- Side-by-side company comparator

### 📄 Export Report
- CSV export
- Excel export with separate sheets per risk tier

### 🎯 Recommendations
- Similar company finder using cosine similarity
- Comparison chart
- Safer investment alternatives
- Investment summary

### 📰 News & Sentiment
- Latest news fetched via NewsAPI
- Sentiment analysis (Positive/Neutral/Negative)
- ESG impact assessment
- Article cards with source and date

---

## 🧠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Streamlit |
| Backend | Python |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Plotly, Seaborn, Matplotlib |
| Authentication | Bcrypt + Google Sheets |
| News API | NewsAPI.org |
| Export | OpenPyXL |
| Deployment | Streamlit Community Cloud |
| Version Control | Git & GitHub |
| Android | Android Studio + Kotlin (WebView) |

---

## 📊 ML Models Used

| Model | Purpose |
|---|---|
| Random Forest | Primary risk prediction |
| Logistic Regression | Baseline classification |
| Gradient Boosting | Advanced risk prediction |

**Risk Categories:**
- ✅ **Low Risk** — ESG Score ≥ 70
- ⚠️ **Medium Risk** — ESG Score 45–70
- 🚨 **High Risk** — ESG Score < 45

---

## 📁 Dataset

The platform accepts any CSV dataset with the following columns:
- `name` / `company` — Company name
- `environment_score` — Environmental score
- `social_score` — Social score
- `governance_score` — Governance score

**Recommended Dataset:**
[Public Company ESG Ratings — Kaggle](https://www.kaggle.com/datasets/alistairking/public-company-esg-ratings-dataset)

---

## ⚙️ How to Run Locally

### Prerequisites
- Python 3.8+
- Git

### Steps

```bash
# Clone the repository
git clone https://github.com/varshitha201005/esg-risk-platform.git

# Navigate to project folder
cd esg-risk-platform/esg-risk-platform1

# Create virtual environment
python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

---

## 📱 Android App

An Android APK is available that wraps the web app in a native Android shell.

- Built with Android Studio
- Uses WebView to load the Streamlit app
- Works on Android 7.0+ (API 24+)
- [⬇️ Download TripleLens APK](https://github.com/varshitha201005/esg-risk-platform1/releases/download/v1.0.0/TripleLens-v1.0.0.apk)

---

## 🎯 ESG Scoring Formula
ESG Score = (Environmental × 40%) + (Social × 30%) + (Governance × 30%)

---

## 👩‍💻 Developer

**Varshitha Sharigudam**
🎓 B.Tech Data Science Student — Mahatma Gandhi Institute of Technology

[![Email](https://img.shields.io/badge/Email-varshithasharigudam@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:varshithasharigudam@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/varshitha-sharigudam-8b36722b8/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/varshitha201005)
[![Live Demo](https://img.shields.io/badge/Live_Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://esg-risk-platform-q9uc8ktfzwtu3ny6mpeepe.streamlit.app)
---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

- [Streamlit](https://streamlit.io) — Web framework
- [Scikit-learn](https://scikit-learn.org) — Machine learning
- [Kaggle](https://kaggle.com) — Dataset source
- [Plotly](https://plotly.com) — Interactive charts
- [NewsAPI](https://newsapi.org) — News data
- [Google Sheets](https://sheets.google.com) — User database
