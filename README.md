# 🚚 Amazon Delivery Performance Analysis – EDA Project

Exploratory Data Analysis of a delivery dataset to uncover insights into delivery time, ratings, and operational efficiency across demographics, geography, and environmental conditions.

---

## 🎯 Project Objective

- Identify factors that influence **delivery pickup duration** and **delivery personnel ratings**
- Extract actionable insights for optimizing service efficiency and customer satisfaction

---

## 🗂️ Dataset Features

Includes:
- **Delivery details**: Order & pickup timestamp, restaurant and delivery coordinates
- **Personnel info**: Age, rating, vehicle type, condition, multiple deliveries
- **External conditions**: Weather, traffic density, city type, festival indicator
- **Order characteristics**: Type of order

---

## 🛠️ Tools & Technologies

- Python: Pandas, NumPy, Matplotlib, Seaborn
- Jupyter Notebook (analysis & visualization)
- Git & GitHub for version control
- Tableau Public for dashboard export

---

## 🧪 Analysis Overview

### 1. Data Cleaning & Feature Engineering
- Converted time columns to `datetime`, handled midnight crossovers  
- Calculated **pickup duration** in hours
- Computed **Haversine-based delivery distances**  
- Created **age group** bins for delivery personnel

### 2. Univariate & Bivariate Visualizations
- Distribution plots for age, ratings, distances  
- Box and bar plots comparing delivery time vs categorical variables  

### 3. Correlation Analysis
- Heatmap of numerical feature correlations  
- Identified weak-to-moderate relationships between pickup time and factors like distance, multiple deliveries, vehicle condition

### 4. In-depth Analysis for Age Group 26–35
- Subgroup chosen for having largest representation but lower average ratings  
- Analyzed impact of:
  - `multiple_deliveries`
  - `traffic_density`
  - `vehicle_type`
  - `vehicle_condition`
  - `festival`, `city`
- Visualized via combined subplots for comparative insights

---

## 📊 Key Insights

- **Age vs Ratings**: Highest ratings belong to the 46–50 group; 26–35 shows greater variation and slightly lower average scores  
- **Operational Factors**:
  - Increased **distance** and **multiple deliveries** mildly lengthen pickup time  
  - Better **vehicle condition** correlates with faster pickup  
- **Environmental Impact**:
  - High **traffic** or **festival days** slightly lower ratings and increase pickup duration  
  - Bike and motorbike-based deliveries score better ratings than scooters in the 26–35 group

---

## 🧭 Business Implications

- **Allocate fewer simultaneous deliveries** to maintain high ratings  
- **Prioritize upkeep of delivery vehicles** to boost performance  
- **Prepare contingency strategies** during festivals and busy hours  
- Consider **age-based routing and fairness**, ensuring newer staff within high-volume age group receive training and support

---

## 📂 Repository Structure

amazon-delivery-analysis-EDA/
├── data/ # Raw and processed CSV files
├── notebooks/
│ └── amazon_delivery_analysis.ipynb
├── visuals/ # Key charts and heatmaps
├── README.md
└── requirements.txt


---

## 🕵️ Why It Stands Out

- Demonstrates **strong storytelling** with real-world context  
- Highlights **domain knowledge** in logistics and performance analysis  
- Includes **multiple types of visualizations** (heatmaps, boxplots, combined charts)  
- Features **thoughtful feature engineering** and subgroup analysis  
- Ready to be extended into **predictive modeling or dashboard reports**

---

## 🚀 Next Steps

- Build a **predictive model** (e.g., regression or classification) for delivery time/rating  
- Deploy as a **dashboard (Tableau, Streamlit, etc.)** to interactively explore insights  
- Document process and assumptions in a **LinkedIn article or case study**

---

## 🧷 Contact & Links

- GitHub Portfolio: https://github.com/pui1ya  
- LinkedIn: https://www.linkedin.com/in/punya-shree-s-624a40293/
- Tableau: https://public.tableau.com/app/profile/punya.shree.s8511/viz/Book1_17538833500480/Dashboard1?publish=yes  

---

🔍 **Feel free to reach out if you'd like feedback or help extending this project into a delivery time prediction model or interactive dashboard.**

