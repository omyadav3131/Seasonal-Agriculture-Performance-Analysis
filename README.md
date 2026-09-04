# 🌾 Seasonal Agriculture Performance Analysis

<p align="center">
  <b>VOIS Data Analytics Major Project</b><br>
  Turning agricultural data into insights for better seasonal, crop, irrigation, and profitability decisions.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analytics-blue?logo=python">
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-orange?logo=googlecolab">
  <img src="https://img.shields.io/badge/Pandas-Analysis-150458?logo=pandas">
  <img src="https://img.shields.io/badge/Seaborn-Visualization-4C9A2A">
  <img src="https://img.shields.io/badge/VOIS-Major%20Project-red">
</p>

---

## 📌 About the Project

**Seasonal Agriculture Performance Analysis** is a data analytics project developed as part of the **VOIS Data Analytics Major Project**.

The project analyzes **4,000 agricultural farm records across 28 variables** to understand how agricultural performance changes across:

- 🌦️ Seasons
- 🌱 Crops
- 💧 Irrigation methods
- 🌍 Environmental conditions
- 💰 Production and profitability
- 🚰 Water usage and efficiency
- 🦠 Disease & pest risk

The objective is to transform raw agricultural data into meaningful insights that can support **crop selection, irrigation planning, resource management, and profitability decisions**.

---

## 🎯 Project Objectives

| Objective | Focus |
|---|---|
| 🌾 Seasonal Analysis | Compare Kharif, Rabi and Zaid performance |
| 🌱 Crop Analysis | Evaluate yield, production and profitability |
| 💧 Irrigation Analysis | Compare irrigation methods and water efficiency |
| 🌦️ Environmental Analysis | Study relationships between environmental factors and outcomes |
| 📊 Statistical Analysis | Identify statistically significant differences |
| 💰 Economic Analysis | Identify profitable and loss-making crop-season combinations |
| 💡 Recommendations | Convert analytical findings into practical insights |

---

## 🗂️ Dataset

The dataset contains:

**4,000 records × 28 variables**

It includes information related to:

- Farm and geographic characteristics
- Crop and seasonal information
- Environmental conditions
- Farming inputs
- Irrigation methods
- Yield and production
- Market price
- Costs
- Profit
- Water usage
- Disease and pest risk

### Data Quality

| Check | Result |
|---|---:|
| Records | 4,000 |
| Variables | 28 |
| Missing Values after Cleaning | 0 |
| Duplicate Rows | 0 |
| Duplicate Farm IDs | 0 |
| Outliers | Identified and retained |

---

## 🧹 Data Preparation

The dataset was prepared before analysis through:

- Missing-value detection
- Group-based median imputation
- Duplicate checking
- Data type verification
- Categorical-value inspection
- State–district consistency checking
- Outlier identification
- Creation of a cleaned analysis dataset

Missing numerical values were imputed using **Crop + Season group medians**.

---

## 📊 Analysis Performed

### 🌦️ Seasonal Performance

Performance was compared across:

**Kharif → Rabi → Zaid**

Metrics included:

- Average yield
- Production
- Profit
- Water efficiency
- Disease & pest risk

### 🌱 Crop Performance

Crops were compared using:

- Average yield
- Average profit
- Profitability rate
- Crop × Season performance

### 💧 Irrigation Analysis

Irrigation methods analyzed:

- Drip
- Sprinkler
- Rainfed
- Flood

The analysis covered:

- Yield
- Profit
- Water usage
- Water efficiency

### 🔬 Statistical Analysis

Statistical techniques included:

- One-way ANOVA
- Tukey HSD post-hoc testing
- Correlation analysis
- Regression analysis
- Comparative analysis

---

## 🏆 Key Findings

### 🥇 Seasonal Performance

**Kharif** showed the strongest overall performance, while **Zaid** generally showed weaker performance.

### 💰 Most Profitable Crops

| Crop | Average Profit |
|---|---:|
| 🌱 Sugarcane | ₹817,187.99 |
| 🌶️ Chilli | ₹750,878.34 |
| 🌿 Cotton | ₹124,546.92 |
| 🥜 Groundnut | ₹44,858.12 |

Sugarcane and Chilli were the strongest crops by profitability.

### 💧 Irrigation Performance

**Drip irrigation** recorded the highest average yield and profit among the irrigation methods analyzed.

**Rainfed** farming showed the highest water efficiency, while **Flood irrigation** showed the lowest.

### 🌦️ Environmental Relationships

Environmental variables such as rainfall, temperature, humidity, sunlight, soil moisture and soil pH showed **weak linear correlations with yield** in this dataset.

### 📈 Yield & Profit

Yield and profit showed a **moderate positive relationship**, indicating that higher yield was generally associated with higher profitability.

---

## 📐 Statistical Evidence

Statistical testing provided additional evidence for important differences.

### Seasonal Yield

When all crops were included, seasonal yield differences were not statistically significant.

After excluding **Sugarcane**, seasonal yield differences became statistically significant:

> **F = 61.2526, p < 0.001**

Tukey HSD indicated significant pairwise differences between the seasons.

### Irrigation Yield

Irrigation-wise yield differences were statistically significant:

> **F = 4.6706, p = 0.00292**

Drip showed significant yield differences compared with Flood and Rainfed irrigation.

---

## 💡 Business & Agricultural Insights

The analysis suggests several practical directions:

**01 — Prioritize suitable Kharif cultivation**  
Kharif demonstrated stronger overall seasonal performance.

**02 — Evaluate high-profit crops**  
Sugarcane and Chilli showed strong profitability in the analyzed dataset.

**03 — Improve irrigation decisions**  
Drip irrigation showed strong yield and profit performance.

**04 — Manage water resources carefully**  
Flood irrigation showed the lowest water efficiency and should be reviewed where alternatives are practical.

**05 — Review loss-making combinations**  
Maize, Rice and Wheat showed several low-profit or loss-making crop-season combinations.

**06 — Use environmental variables carefully**  
Environmental factors should be considered as supporting indicators rather than single-variable decision rules.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| 🐍 Python | Data analysis |
| 🐼 Pandas | Data manipulation |
| 🔢 NumPy | Numerical computing |
| 📊 Matplotlib | Visualization |
| 🎨 Seaborn | Statistical visualization |
| 🧪 SciPy | Statistical analysis |
| 📐 Statsmodels | Statistical modelling |
| ☁️ Google Colab | Development environment |
| 📗 Microsoft Excel | Dataset format |

---
## 📁 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── 📓 Seasonal_Agriculture_Performance_Analysis.ipynb
├── 📊 seasonal_agriculture_performance_dataset (2).xlsx
└── 📄 README.md
