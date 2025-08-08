# 🏏 SQL Final Project – IPL Auction Strategy

![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue?style=for-the-badge&logo=postgresql)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-green?style=for-the-badge)
![Cricket](https://img.shields.io/badge/Domain-IPL%20Cricket-orange?style=for-the-badge)

---

## 📌 Project Overview

This project focuses on **designing an IPL auction strategy** for a new franchise by analyzing past IPL match and player performance data.  
Using SQL queries, we identify top-performing batsmen, bowlers, all-rounders, and wicketkeepers to create a balanced and competitive team.

---

## 🎯 Objectives

1. **Batsmen Selection** – Identify 10 batsmen with the highest strike rates (min. 500 balls faced).  
2. **Consistent Performers** – List 10 players with the best batting average (min. 2 seasons or 28 matches).  
3. **Boundary Hitters** – Find 10 players with the most runs in boundaries (min. 2 seasons or 28 matches).  
4. **Economical Bowlers** – List 10 bowlers with the best economy (min. 500 balls bowled).  
5. **Strike Rate Bowlers** – Identify 10 bowlers with the best bowling strike rate (min. 500 balls bowled).  
6. **Top All-Rounders** – Players excelling in both batting and bowling strike rates (min. 500 balls faced & 300 balls bowled).  
7. **Wicketkeeper Evaluation** – Multi-criteria scoring system for selecting top wicketkeepers.  

---

## 📂 Datasets Used

- `IPL_Ball` – Ball-by-ball match data.  
- `IPL_matches` – Match-level details.  
- Additional processed tables: `deliveries`, `deliveries_v02`, `deliveries_v03`.

---

## 🛠 Queries & Insights

The project uses **advanced SQL queries** to:
- Create tables and transform raw datasets.
- Apply filtering conditions, aggregations, and joins.
- Use `CASE WHEN` for conditional columns like `ball_result` (boundary, dot, other).
- Rank and order players based on calculated metrics.
- Merge multiple datasets for enriched analysis.

---

## 📊 Example Insights

- **Batsmen:** Found top scorers with exceptional strike rates and averages.
- **Bowlers:** Isolated economical bowlers and those with high wicket-taking ability.
- **All-rounders:** Balanced contributors in both batting and bowling.
- **Wicketkeepers:** Ranked using batting, adaptability, fielding skills, leadership, versatility, consistency.

---

## 🏆 Wicketkeeper Selection Criteria

Weighted scoring system based on:
- Batting Ability
- Adaptability
- Fielding Skills
- Communication & Leadership
- Versatility
- Consistency & Experience

**Example Outcome:** W2 and W5 emerged as the top 2 wicketkeepers.

---

## 📈 Additional Analyses

- City-wise match counts.
- Team boundary and dot ball counts.
- Dismissal type distributions.
- Top bowlers by extra runs conceded.
- Venue-based and year-wise run totals.

---

## 📜 How to Use

1. Import datasets into your SQL environment.
2. Run the table creation queries to set up `IPL_Ball` and `IPL_matches`.
3. Execute analytical queries to generate player and team insights.
4. Apply the scoring system for role-specific player selection.

---

## 📄 Author

**Vaishnavi Gupta**  

---

## 📜 License

This project is licensed under the MIT License — free to use, modify, and share.

---

<p align="center">Thank you!!!</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/02d0eecb-7d96-4970-b03a-f284089287ed" alt="Sticker Image">
</p>

<p align="center">...</p>

<p align="center"> Have a cup of coffee ;)
</p>
<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYm4yYXhqbHhrOHE4bGE2MWg4OXJ1andlZGkyajloaHhlZWx4cWRpMiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/ES4Vcv8zWfIt2/giphy.gif">
</p>


