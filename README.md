
# 📊 Netflix Dataset Analysis (Top 1000 Titles)

This project explores and visualizes the **Netflix Titles (Top 1000)** dataset using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**. The goal is to gain insights into content types, durations, countries of origin, release trends, genres, and more.

---

## 📁 Dataset

- **Source:** `netflix_titles_1000.csv`  
- **Columns used:** `type`, `title`, `director`, `cast`, `country`, `release_year`, `rating`, `duration`, `listed_in`

---

## 🔍 Key Features & Visualizations

1. **🎬 Count of Movies vs TV Shows**  
   → Bar chart showing how many movies and TV shows are in the dataset.

2. **🌍 Top Countries Producing Content**  
   → Bar chart of top 7 countries contributing the most content.

3. **📅 Trend of Content Production Over Years**  
   → Histogram showing yearly distribution of content releases.

4. **🎭 Top 10 Most Common Genres**  
   → Bar chart of the most frequent genres on Netflix.

5. **⏱️ Duration Distribution of Movies & TV Shows**  
   → Violin plot showing how long the content typically is.

6. **🎥 Top 5 Directors with Most Content**  
   → Bar chart showcasing directors with the highest contributions.

7. **🔞 Content Rating Distribution**  
   → Pie chart representing the distribution of Netflix content ratings.

8. **📈 Correlation Heatmap (Numerical Data)**  
   → Heatmap showing relationships between numeric values in the dataset.

---

## 📌 Observations

- **Movies dominate** the platform compared to TV Shows.
- **United States** leads in content production, followed by **India** and the **UK**.
- The **peak year** for content release was identified using historical trends.
- Most common genres are **Drama**, **Comedy**, and **Action**.
- **TV shows** have shorter "duration" values due to representing seasons, not minutes.
- **TV-MA** and **PG-13** are the most used content ratings.

---

## 🧰 Tech Stack

- **Python** 3.x
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/netflix-analysis.git
   cd netflix-analysis
