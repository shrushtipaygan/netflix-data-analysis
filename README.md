# 🎬 Netflix Data Analysis

Exploratory Data Analysis (EDA) of Netflix movies and TV shows dataset to uncover trends, patterns, and insights about content popularity, genres, ratings, and release history.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Key Insights](#key-insights)
- [Technologies Used](#technologies-used)

---

## Overview

This project performs an in-depth exploratory data analysis on a Netflix movies dataset. The goal is to understand what kinds of content are most popular, how genres differ in audience reception, and how the volume of releases has changed over time — all through interactive visualizations.

---

## Dataset

**File:** `NetflixData.csv`

| Column | Description |
|---|---|
| `Release_Date` | Date the movie/show was released |
| `Title` | Name of the movie/show |
| `Overview` | Short description of the content |
| `Popularity` | Popularity score (numeric) |
| `Vote_Count` | Number of audience votes |
| `Vote_Average` | Average audience rating (out of 10) |
| `Original_Language` | Language of the original content |
| `Genre` | Genre(s) associated with the title |
| `Poster_Url` | URL link to the movie/show poster |

---

## Project Structure

```
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main Jupyter Notebook with full EDA
├── NetflixData.csv               # Dataset
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Netflix-Data-Analysis.git
   cd Netflix-Data-Analysis
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate        # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `Netflix_Data_Analysis.ipynb` and run all cells.

> **Note:** If running on Google Colab, upload `NetflixData.csv` to `/content/` and run the notebook directly.

---

## Key Insights

- 🎭 **Drama** is the most frequently occurring genre in the dataset, reflecting Netflix's heavy investment in dramatic content.
- 🏆 **Adventure** movies have the highest average popularity, showing strong audience engagement with high-energy storytelling.
- 🚀 **Action** and **Science Fiction** also rank highly in audience interest and vote counts.
- 📈 Movie releases increased significantly **after the year 2000**, reflecting the rapid growth of the global film industry and streaming platforms.
- 📊 The popularity distribution is **highly skewed** — most titles are average, while only a few become blockbuster hits.

---

## Technologies Used

- **Python 3.x**
- **Pandas** – Data loading, cleaning, and manipulation
- **Plotly Express** – Interactive data visualizations
- **Jupyter Notebook** – Development and presentation environment
