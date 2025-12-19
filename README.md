# 🚗 Used Car Price Analysis – Hyderabad

## 📌 Project Overview
This project is an end-to-end **Data Analytics project** focused on analyzing used car listings in the Hyderabad region.
The data was scraped from an online automobile marketplace using Python and Selenium, cleaned using Pandas, and visualized using a BI tool to derive actionable insights.

The objective of this project is to understand **pricing trends, brand value, mileage impact, fuel type dominance, and buyer-friendly segments** in the used car market.

---

## 🛠 Tools & Technologies Used
- **Python**
  - Selenium (Web Scraping)
  - BeautifulSoup
  - Pandas & NumPy
- **Jupyter Notebook**
- **Power BI / Tableau** (for dashboard & visualization)
- **Excel** (basic validation)
- **Git & GitHub**

---

## 🔄 Project Workflow
1. **Web Scraping**
   - Scraped used car listings for Hyderabad location
   - Extracted attributes such as price, brand, model, year, fuel type, transmission, mileage, and kilometers driven
   - The project follows a layered data architecture approach (Raw → Clean → External) similar to production analytics pipelines

2. **Data Cleaning & Preprocessing**
   - Removed null and duplicate values
   - Standardized price and mileage formats
   - Extracted year of manufacture
   - Corrected inconsistent units and text-based values

3. **Exploratory Data Analysis**
   - Price distribution analysis
   - Brand-wise and fuel-type-wise comparisons
   - Mileage vs price relationships

4. **Dashboard Creation**
   - Interactive visuals for price range, brand comparison, fuel type dominance, and mileage impact

5. **Insights & Conclusion**
   - Derived market trends and buyer-focused insights

---

## 📊 Key Insights
- Cars priced between **₹3–6 lakhs** dominate the used car market
- **Maruti and Tata** provide the best value-for-money options
- **Lower kilometers driven cars** command higher resale prices
- **Newer cars (2019+)** are priced significantly higher
- **Petrol cars** dominate the listings compared to diesel and others

---

## 📁 Project Structure
Used-Car-Analysis/
│
├── data/
│   ├── clean/       # Cleaned city-wise datasets
│   ├── raw/         # Scraped raw datasets
│   └── external/    # Final dataset used for dashboard
│
├── scripts/
│   ├── raw/         # Web scraping scripts
│   ├── clean/       # Data cleaning scripts
│   └── external/    # Data merging & transformation scripts
│
├── docs/
│   ├── dashboard/   # Power BI / Tableau dashboard
│   ├── presentation/ # Project presentation
│   └── report/      # Detailed project report
│
├── README.md
├── requirements.txt
└── .gitignore


---

## ⚠ Limitations
- Data sourced from a **single website**
- Limited to **Hyderabad region**
- No historical price trends available
- Some mileage values required manual validation

---

## 🚀 Future Enhancements
- Add machine learning model for **price prediction**
- Expand data scraping to multiple cities
- Automate scheduled data collection
- Add comparison between seller types

---

## 👤 Author
**Shreyas Jaronde**  
Aspiring Data Analyst | Python | SQL | Data Visualization

