# 📊 DNA of a Hit Song: A Data-Driven Investigation

This project investigates what makes a song popular using a data-driven approach based on Spotify audio features. It explores whether song success can be explained through measurable attributes or if it emerges from more complex patterns.

---

## 📌 Overview

The project follows a structured analytical progression:

1. Individual feature analysis  
2. Balance of musical attributes  
3. Interaction between features  
4. External influences beyond audio features  

The study identifies that popularity is not determined by a single factor but by a combination of patterns referred to as the **“DNA of a Hit Song.”**

---

## 🎯 Objectives

- Analyze relationships between audio features and song popularity  
- Test common assumptions about hit songs  
- Identify deeper patterns beyond individual features  
- Understand the role of feature interactions and external factors  

---

## 📊 Dataset

- Approximately 191,000 songs  
- Structured tabular data from Spotify  

### Key Features

- Danceability  
- Energy  
- Valence  
- Tempo  
- Loudness  
- Acousticness  
- Duration  

### Target Variable

- Popularity (0–100)

---

## ⚙️ Data Preprocessing

- Removed missing values  
- Eliminated duplicate records  
- Verified data types and feature ranges  

---

## 📈 Exploratory Data Analysis (EDA)

### Observations

- Most songs fall within a moderate popularity range (40–60)  
- Highly popular songs are rare  
- Feature distributions show:
  - Moderate danceability  
  - Generally high energy  
  - Tempo concentrated between 80–130 BPM  

### Correlation Insights

- Weak relationships between most features and popularity  
- No single feature strongly explains song success  

---

## 🧪 Hypothesis-Based Analysis

### 1. Individual Features

- Features like danceability, duration, and liveness show trends  
- None independently determine popularity  

---

### 2. Balance of Features

- Moderate values outperform extremes  
- Optimal ranges observed for:
  - Energy  
  - Valence  

→ Popularity is higher when features are balanced  

---

### 3. Feature Interactions

- Combined features explain popularity better:
  - Danceability + Energy  
  - Energy + Valence  
  - Speechiness + Instrumentalness  

→ Popularity emerges from interaction between multiple features  

---

### 4. External Influences

Engineered metrics:

- Feature scores (normalized)  
- DNA Match Score  
- Feature Consistency Ratio  
- Feature Variability  

Findings:

- Better feature alignment increases likelihood of success  
- External factors significantly impact popularity:
  - Artist influence  
  - Genre  
  - Platform exposure  

→ External influence can boost popularity even when feature alignment is low  

---

## 📊 Visualizations Used

- Histograms  
- Binned bar charts  
- Stacked bar charts  
- Heatmaps  
- Line charts  

Used for both single-variable and multi-variable analysis  

---

## 🧠 Key Findings

- No single feature predicts popularity  
- Balanced attributes perform better than extremes  
- Feature interactions are critical  
- External factors play a major role  

---

## 🧾 Conclusion

Song popularity is influenced by:

- Balanced musical characteristics  
- Interaction between multiple features  
- External factors such as promotion and visibility  

The “DNA of a Hit Song” is not a fixed formula but a combination of these elements.
