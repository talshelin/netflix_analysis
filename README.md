# 🎬 Netflix Content Library — Exploratory Data Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=flat-square" />
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-4c72b0?style=flat-square" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
</p>

<p align="center">
  A comprehensive EDA of the Netflix catalog dataset — covering content types, genres, countries, ratings, directors, actors, and release trends.
</p>

---

## 📌 Project Overview

This project explores the **Netflix Movies and TV Shows** dataset to uncover patterns in content distribution, audience targeting, geographic diversity, and platform growth over time. The analysis was conducted entirely in Python using a Jupyter Notebook.

> **Key question:** What does the Netflix catalog tell us about the platform's content strategy?

---

## 📁 Project Structure

```
netflix-analysis/
│── netflix_titles.csv          # Raw dataset
│── Netflix_EDA.ipynb           # Main analysis notebook
│
├── README.md
```

---

## 📊 Dataset

| Feature        | Description                                        |
| -------------- | -------------------------------------------------- |
| `show_id`      | Unique ID for each title                           |
| `type`         | Movie or TV Show                                   |
| `title`        | Title of the content                               |
| `director`     | Director(s)                                        |
| `cast`         | Main cast                                          |
| `country`      | Country of origin                                  |
| `date_added`   | Date added to Netflix                              |
| `release_year` | Year of original release                           |
| `rating`       | Audience rating (TV-MA, PG-13, etc.)               |
| `duration`     | Duration in minutes (movies) or seasons (TV shows) |
| `listed_in`    | Genre tags                                         |
| `description`  | Short description                                  |

**Source:** [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🔍 Analysis Sections

### 1. Content Type Distribution

- Movies dominate at **69.62%** of all content
- TV Shows account for **30.38%**
- Approx. **4,500 movies** vs **3,900 TV shows**

### 2. Release Year Trends

- Peak content years: **2017–2019** (600+ titles/year)
- Sharp drop post-2019 likely due to COVID-19 production halts
- Pre-2000 content is minimal — catalog skews contemporary

### 3. Movies vs. TV Shows Over Time

- Both formats grew exponentially from ~2010 onward
- Movie peak: ~750 titles/year around 2019–2020
- TV Show peak: ~400+ titles/year in the same period

### 4. Geographic Distribution

- 🇺🇸 **United States** — ~69% of all content
- 🇮🇳 **India** — ~14% (strong Bollywood presence)
- 🇬🇧 **United Kingdom** — ~7%
- 🇯🇵 **Japan** — ~4.5%
- 🇰🇷 **South Korea** — ~3.6%

### 5. Ratings Analysis

- **TV-MA** is the most common rating (3,000+ titles)
- Adult audience focus: TV-MA + TV-14 account for ~60% of catalog
- Children's content mainly delivered via TV shows (TV-G, TV-Y ratings)

### 6. Genre Insights

**Movies:** Dramas, Documentaries, and Stand-Up Comedy dominate  
**TV Shows:** Kids' TV and Crime Dramas are top categories  
**Individual genres:** TV Horror, Anime Features, and Cult Movies lead

### 7. Director & Actor Analysis

- Top director: **Rajiv Chilaka** (~22 titles)
- Top actor: **Anupam Kher** (~39 titles)
- Indian (Bollywood) and Japanese (anime) talent heavily represented

### 8. Movie Duration

- **Mean:** ~99.6 minutes | **Median:** 98 minutes
- Distribution is near-normal, centered at 90–100 min
- Outliers reach up to 300 minutes (long documentaries)

### 9. TV Show Seasons

- **Median:** 1 season | **Mean:** 1.78 seasons
- Over 1,800 shows have only 1 season
- Netflix strongly favors **limited series** format

---

## Key Visualizations

| Chart                  | Type                | Insight                                       |
| ---------------------- | ------------------- | --------------------------------------------- |
| Type of contents       | Bar + Pie           | 70/30 Movie vs TV split                       |
| Release year           | Bar                 | Peak 2017–2019                                |
| Movies vs TV over time | Line                | Explosive post-2010 growth                    |
| Top 5 countries        | Pie + Bar           | US & India dominate                           |
| Ratings distribution   | Bar                 | TV-MA leads across all ratings                |
| Top genres             | Horizontal Bar      | Dramas & Docs top movies; Kids' TV tops shows |
| Top directors/actors   | Horizontal Bar      | Bollywood & anime talent prominent            |
| Movie duration         | Boxplot + Histogram | ~99 min average                               |
| Season distribution    | Bar                 | Single-season majority                        |

---

## Setup & Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/netflix-analysis.git
cd netflix-analysis


# Launch Jupyter
jupyter notebook notebooks/netflix_EDA.ipynb
```

---

## Key Takeaways

1. **Netflix is movie-heavy** but growing its TV Show investment, especially in limited series
2. **US content dominates**, but India, South Korea, and Japan are strong regional players
3. **Mature audiences** are the primary target — TV-MA content is #1 across both formats
4. **International dramas** and **anime** are Netflix's fastest-growing genre segments
5. **Post-2019 dip** signals pandemic impact on production, not platform decline
6. The typical Netflix movie runs ~**99 minutes**; the typical Netflix TV show has **1 season**

---

## License

This project is licensed under the MIT License. The dataset is publicly available on Kaggle under its respective terms.

---
