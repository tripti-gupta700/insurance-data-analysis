# Insurance Data Analysis & EDA Project

📊 **Project Overview**
---
As part of my transition from web development to data analysis & machine learning, I undertook this mini project to practice the complete data analysis pipeline using Python. 

Over the last week, I learned and applied:
- Python libraries crucial for data analysis: `pandas`, `numpy`, `seaborn`, `matplotlib`
- Core machine learning concepts: supervised, unsupervised, and reinforcement learning
- The step-by-step approach to building a data analysis & ML project.

---

## 📁 Dataset
- Used a public `insurance.csv` dataset containing information on:
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`
- Goal: analyze the dataset, engineer features, and prepare data for predictive modeling.

---

## 🚀 What I did
### 🔍 1. Data Exploration
- Loaded the dataset and explored with:
  - `.head()`, `.info()`, `.describe()` to understand structure, types, and missing data.

### 📊 2. Visualization & EDA
- Created visualizations to explore data distributions and relationships:
  - `countplot`, `barplot`, `histograms` to see frequency and spread.
- Explored how variables like `smoker` and `region` impact `charges`.

### 📈 3. Correlation & Statistics
- Computed **Pearson correlation coefficients** to check relationships between numerical features and `charges`.
- Ran **Chi-squared tests** to check statistical independence of categorical variables with binned `charges`.

### 🛠️ 4. Feature Engineering
- Engineered new features, like BMI categories: Normal, Overweight, Obese.
- Converted categorical data into numerical using one-hot encoding.

### ⚖️ 5. Feature Scaling
- Applied scaling techniques to standardize numerical features.

---

## 💡 Why this project matters
- Practiced moving from raw data to meaningful insights.
- Learned to apply statistical tests (Pearson & Chi-squared) to validate assumptions.
- Prepared data for future machine learning modeling.

---

## 🚀 Next Steps
- Build regression models to predict insurance `charges`.
- Evaluate model performance using metrics like MAE, RMSE.

---

## 🔧 Tech Stack
- **Python**: data analysis & scripting
- **pandas & numpy**: data manipulation
- **matplotlib & seaborn**: data visualization
- **scipy.stats**: statistical tests

---

## 📝 How to run
git clone https://github.com/tripti-gupta700/insurance-data-analysis.git
cd insurance-data-analysis
# Install dependencies (example using pip)
pip install pandas numpy matplotlib seaborn scipy
# Run the Jupyter Notebook or Python script

Connect with me
LinkedIn: linkedin.com/in/tripti-gupta-1226a129a

GitHub: https://github.com/tripti-gupta700/

