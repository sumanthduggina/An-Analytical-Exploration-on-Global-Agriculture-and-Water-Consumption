# 🌾 Global Agriculture Production and Water Consumption Analysis

This project explores the relationship between global crop production and water consumption using data from 141 countries. By analyzing how green, blue, and grey water types contribute to agricultural practices, we aim to identify sustainability patterns and opportunities for improved water resource management across the world.

---

## 📊 Project Overview

Water is a critical component in agriculture, and understanding its usage patterns is key to achieving food security and sustainability. This project combines data from various trusted sources such as OECD, Worldometer, Aquastat, and Harvard Dataverse to:

- Evaluate how efficiently different countries use water for crop production.
- Compare water consumption (green, blue, and grey water) across regions and crops.
- Assess the impact of population and land usage on agricultural water withdrawal.

---

## 🔍 Data Collection

We used Python (Pandas, BeautifulSoup, Selenium) to extract and preprocess data from:

- OECD
- Worldometer
- Aquastat
- Harvard Dataverse

Features collected include:
- **Country**
- **Population**
- **Agricultural land (% of total land area)**
- **Crop-specific data (area, production, sector code)**
- **Green, Blue, Grey water intensities**
- **Total water used (by type and in total)**
- **Agricultural water withdrawal (% of renewable resources)**

---

## 🔧 Data Transformation

- Cleaned null values and removed duplicates
- Merged datasets on country names
- Converted codes to human-readable values
- Created derived columns (e.g., Total Green Water = Green Water Intensity × Production)
- Unified datasets into a consolidated format for analysis

---

## 📈 Exploratory Data Analysis (EDA)

We tested several hypotheses including:

1. **Population Size ≠ Higher Rice Production**
2. **Increased Production → More Grey Water Consumption**
3. **High Population ≠ High Total Water Usage**
4. **Agricultural Water Stress is Highest in Asia, MENA Regions**
5. **Water Usage Positively Correlates with Production**
6. **Green Water Usage Dominates Other Sources Across Crops**

---

## 🛠️ Tools & Technologies

- **Languages:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn, BeautifulSoup, Selenium
- **Notebook:** Jupyter
- **Presentation & Report:** PowerPoint & Word

