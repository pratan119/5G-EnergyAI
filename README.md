#  5G-EnergyAI: AI for 5G Energy Consumption Modeling

## 📌 Overview

This project focuses on modeling and predicting **energy consumption in 5G networks** using Artificial Intelligence techniques.
The goal is to analyze network data and build models that can help optimize energy usage in base stations and cells.

---

## 🚀 Features

* Data analysis of 5G network energy consumption
* Data integration from multiple sources (cell-level, base station info)
* Visualization of energy trends and distributions
* Feature engineering (smoothing, transformations)
* Machine Learning models for energy prediction

---

## 📂 Dataset

The project uses the following datasets:

* `ECdata.csv` → Energy consumption data
* `CLdata.csv` → Cell-level data
* `BSinfo.csv` → Base station information

These datasets are merged and processed for training models.

---

## 🛠️ Technologies Used

* Python 
* Jupyter Notebook (.ipynb)
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* FastAI

---

## ⚙️ Project Workflow

1. **Data Loading**

   * Import multiple datasets
   * Parse time-based features

2. **Data Preprocessing**

   * Merge datasets
   * Handle missing values
   * Drop irrelevant columns

3. **Exploratory Data Analysis (EDA)**

   * Energy distribution plots
   * Energy vs time analysis
   * Energy vs load relationship

4. **Feature Engineering**

   * Smoothing techniques (Savitzky-Golay filter)
   * Time-based transformations
   * Removal of low-variance features

5. **Model Training**

   * Train ML models for energy prediction
   * Evaluate using metrics like MAE and MAPE

---

## 📊 Sample Visualizations

* Energy distribution histogram
* Average energy over time
* Energy vs network load

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/5G-EnergyAI.git
cd 5G-EnergyAI
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook 5G_EnergyAI.ipynb
```

---

## 📈 Results

* The model predicts energy consumption based on network parameters
* Helps identify patterns between load and energy usage
* Can be extended for real-time energy optimization
