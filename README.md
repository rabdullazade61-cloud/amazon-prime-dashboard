# 🎬 Amazon Prime Titles — Power BI Dashboard

A dataset and Power BI dashboard analyzing Amazon Prime Video's catalog of movies and TV shows (9,668 titles).

<img width="1195" height="737" alt="Screenshot 2026-08-12 180918" src="https://github.com/user-attachments/assets/10edeaf6-9760-44ec-bee8-b5a150b87ef8" />

## 📊 What's in the dashboard?

| Metric | Value |
|---|---|
| Total Shows | 9.67K |
| Total Genres | 518 |
| Total Directors | 5.77K |
| Movies | 80.82% |
| TV Shows | 19.18% |

**Visuals included:**
- 📈 **Total Shows by Genres** — most common genres (Drama, Comedy, Documentary, etc.)
- ⭐ **Total Shows by Ratings** — breakdown by content rating (13+, 16+, R, 18+, etc.)
- 🌍 **Total Shows by Country** — world map distribution by country
- 🥧 **Total Shows by Movies and TV Show** — Movie vs TV Show split
- 📉 **Total Shows by Release Year** — trend line by release year (1920–2021)

## 📁 Files

| File | Description |
|---|---|
| `amazon_prime_titles.csv` | Raw dataset |
| `amazon_prime_dashboard.pbix` | Power BI dashboard file |
| `images/dashboard_preview.png` | Dashboard screenshot |

## 🗂️ Dataset columns

| Column | Description |
|---|---|
| `show_id` | Unique identifier |
| `type` | Movie / TV Show |
| `title` | Title |
| `director` | Director name |
| `cast` | Cast members |
| `country` | Country of production |
| `date_added` | Date added to the platform |
| `release_year` | Year of release |
| `rating` | Content rating |
| `duration` | Runtime |
| `listed_in` | Genre(s) |
| `description` | Short synopsis |

## 🛠️ Tools used

- **Power BI Desktop** — visualization
- **CSV** — data source

---
⭐ If you find this useful, consider giving the repo a star!
