# Social Media Sentiment Analysis Dashboard

This project analyzes a **social media sentiment dataset** using Python and Power BI to uncover emotional patterns, user engagement, and platform behavior across posts.

---

## Dataset Used

- **Name**: `Sentiment dataset.csv`
- **Columns**:
  - `timestamp`: When the post was made
  - `text`: The actual post content
  - `sentiment`: Emotion category (e.g., Joy, Frustration, Positive)
  - `likes`, `retweets`: Engagement metrics
  - `platform`, `country`, `user`: Metadata

---

## Project Objectives

- Understand the **distribution of emotions** expressed in posts
- Compare **engagement levels** (likes/retweets) across platforms
- Visualize **posting trends by time**
- Reveal **frequent words** used under each sentiment (via NLP)
- Build an **interactive Power BI dashboard**

---

## Python (Preprocessing & NLP)

Before visualization, the dataset was cleaned and enriched using Python:
- Removed duplicates and filled missing values
- Standardized sentiment labels
- Tokenized text and counted word frequency
- Generated:
  - `sentiment_cleaned.csv` (used in Power BI)
  - Word cloud images (per sentiment)
  - Bar charts of top words per emotion

---

## Power BI Visuals

| Visual Type | Description |
|-------------|-------------|
| **Pie Chart** | Sentiment distribution of all posts |
| **Bar Chart** | Average likes per platform |
| **Line Chart** | Sentiment volume trend by time of day |
| **KPI Cards** | Max likes, min retweets, avg token count, total posts |
| **Slicers** | Filter by platform and country |
| **Image Visuals** | Embedded word clouds (optional) |

---

## Dashboard Title

> **"Social Media Sentiment Analysis Dashboard"**  
> *Visualizing User Emotions, Engagement Metrics, and Platform Trends from Text Data*

---

## How to Use

1. Open `sentiment_cleaned.csv` in Power BI
2. Rebuild visuals or import `.pbix` if available
3. Add slicers and visuals as described above
4. Optionally embed images from the NLP step

---

## Tools Used

- **Python (Pandas, Seaborn, WordCloud)**
- **Power BI Desktop**
- **Jupyter Notebook**

---

## Author

Made by Vijay Totla as part of the **Codveda Data Analytics Internship – Level 3 Final Task**.

---

