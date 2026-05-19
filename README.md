# NETFLIX_Dashbord_PowerBI

Interactive Netflix analytics dashboard built with Power BI using Netflix datasets.  
This project focuses on catalog exploration, content distribution, audience analysis, countries production insights, and duration analytics.

---

# 📌 Project Overview

Netflix is one of the world's leading streaming platforms and continuously invests in content production to increase engagement and subscriber retention.

The goal of this project is to analyze and visualize Netflix's catalog through an interactive multi-page Power BI dashboard.

---

# 🎯 Objectives

The dashboard answers key business questions such as:

- What are the most represented genres on Netflix?
- In how many countries is Netflix content available?
- Which countries produce the most content?
- What are the dominant genres by country?
- How has Netflix’s catalog evolved over time?
- What is the distribution between Movies and TV Shows?
- How are movie durations and TV Show seasons distributed?

---

# 📊 Dashboard Pages

## 🏠 Main Page
Overview of Netflix catalog including:
- Total titles
- Movies vs TV Shows
- Genre distribution
- Ratings distribution
- Catalog growth over time
- Global availability

---

## 🎞️ Content Analysis
Detailed analysis of:
- Top 5 countries by content
- Seasonality of added content
- Audience segmentation (Adults, Teens, Family, Kids)
- KPI comparison (N vs N-1)
- Top actors & directors
- Movies & TV Shows categories

---

## 🌍 Countries & Durations Analysis
Insights about:
- Global content footprint
- Total movie hours
- Total TV Show seasons
- Movie duration distribution
- TV Show season breakdown

---

# 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Git & GitHub

---

# 🧹 Data Preparation

The dataset required extensive cleaning and transformation:

- Removed null and blank values
- Split multi-value columns:
  - cast
  - country
  - listed_in
  - director
- Created calculated columns and measures
- Managed duplicated `show_id` values after normalization
- Built custom DAX measures using:
  - `DISTINCTCOUNT`
  - `SUMX`
  - `SUMMARIZE`
  - `RANKX`

---

# 📈 Key KPIs

- 🎬 Total Titles: 8,798
- 🍿 Movies: 6.1K
- 📺 TV Shows: 2.7K
- 🌍 Countries: 123
- 🎭 Categories: 42

---

# 🎨 Dashboard Design

The dashboard was designed using a Netflix-inspired theme:

- Netflix Red: `#E50914`
- Dark Background UI
- Rounded containers
- Interactive slicers
- Multi-page navigation

---

# 📂 Dataset

Dataset used:
- Netflix Titles Dataset


---

# 📄 Dashboard Preview

The complete dashboard preview is available in the PDF file below:

📥 [Download the Netflix Dashboard PDF](Netflix%20Dashbord.pdf)



---

# 🚀 Features

✅ Multi-page interactive dashboard  
✅ Dynamic filtering with slicers  
✅ Top N analysis  
✅ Time-series analysis  
✅ KPI tracking  
✅ Genre and audience segmentation  
✅ Country-level content analysis  
✅ Custom Netflix-style UI  

---

# 📌 Future Improvements

- Add recommendation analysis
- Integrate Rotten Tomatoes scores
- Add predictive analytics
- Deploy dashboard to Power BI Service

---

# 👨‍💻 Author

Data Analytics Portfolio Project developed with Power BI.
