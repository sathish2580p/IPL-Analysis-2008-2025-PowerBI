# 🏏 IPL Analysis Dashboard (2008–2025) | Power BI

## 📌 Project Overview

This Power BI project provides an interactive analysis of the Indian Premier League (IPL) from 2008 to 2025. The dashboard enables users to explore team performance, player statistics, season-wise trends, venue analysis, and match insights through interactive visualizations.

---

## 🎯 Objectives

- Analyze IPL performance from 2008–2025
- Compare teams across seasons
- Evaluate player batting and bowling performance
- Identify top performers
- Analyze venue and toss statistics
- Build interactive dashboards for better decision-making

---

## 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Microsoft Excel / CSV

---

## 📊 Dashboard Features

- Executive Dashboard
- Team Performance Analysis
- Player Performance Analysis
- Season-wise Analysis
- Venue Analysis
- Match Summary
- Interactive Filters & Slicers

---

## 📂 Dataset

The project uses IPL historical datasets containing:

- Matches
- Deliveries
- Players
- Teams
- Venues
- Seasons

---

## 📸 Dashboard Preview

![Uploading ipl dashboard.png…]()


## 📈 Key Insights

- Team with the highest number of wins.
- Most successful IPL captain.
- Orange Cap winners across seasons.
- Purple Cap winners across seasons.
- Highest individual score.
- Best bowling figures.
- Venue-wise winning trends.
- Toss decision impact on match results.
- Season-wise total matches.
- Top run scorers and wicket takers.

---

## 📐 DAX Measures Used

Examples:

```DAX
Total Matches = COUNT(Matches[Match_ID])

Total Runs = SUM(Deliveries[Total_Runs])

Average Score = AVERAGE(Deliveries[Total_Runs])

Win Percentage =
DIVIDE(
    [Total Wins],
    [Total Matches]
)

Strike Rate =
DIVIDE(
    SUM(Batting[Runs]) * 100,
    SUM(Batting[Balls])
)
```

---

## 💡 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- Power Query
- DAX
- KPI Design
- Interactive Dashboards
- Data Visualization
- Business Intelligence
- Sports Analytics

---

## 📁 Repository Contents

- Power BI (.pbix) File
- Dataset
- Dashboard Screenshots
- README Documentation

---

## 👨‍💻 Author

**Pamula Sathish**

LinkedIn:(https://www.linkedin.com/in/sathish-pamula-980852267)

GitHub:(https://github.com/sathish2580p)
