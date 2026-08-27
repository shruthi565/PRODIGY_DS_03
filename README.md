# PRODIGY_DS_04 - Social Media Sentiment Analysis and Visualization

## 📌 Task-04

Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.

## 📖 Introduction

Social media platforms contain a large amount of user-generated content that reflects people's opinions and attitudes toward different topics, products, and brands.

In this task, the Twitter social media dataset provided by Prodigy InfoTech is analyzed using Python. The dataset contains tweets associated with different entities and sentiment categories.

The data is cleaned and explored, and visualizations are created to understand the overall sentiment distribution and sentiment patterns across different entities or topics.

## 🎯 Objectives

- Analyze sentiment patterns in Twitter social media data.
- Clean and preprocess the dataset for analysis.
- Identify the distribution of Positive, Negative, Neutral, and Irrelevant sentiments.
- Visualize the sentiment distribution using graphs.
- Analyze sentiment patterns across different entities or topics.
- Identify entities with higher positive or negative sentiment.
- Gain insights into public opinion toward different topics or brands.

## 📊 Dataset

**Dataset:** Twitter Training Dataset

**Source:** Prodigy InfoTech Data Science Datasets - Task 04

The dataset contains Twitter posts associated with different entities and their corresponding sentiment labels.

### Main Columns

| Column | Description |
|---|---|
| ID | Unique identifier associated with the tweet |
| Entity | Topic, product, brand, or entity mentioned in the tweet |
| Sentiment | Sentiment category of the tweet |
| Tweet | Text content of the tweet |

### Sentiment Categories

- **Positive** - Expresses a positive opinion.
- **Negative** - Expresses a negative opinion.
- **Neutral** - Expresses a neutral opinion.
- **Irrelevant** - The tweet is not relevant to the particular entity.

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## 🔧 Data Cleaning

The following data cleaning steps were performed:

1. Loaded the Twitter dataset.
2. Assigned appropriate column names to the dataset.
3. Checked the dataset structure and information.
4. Checked for missing values.
5. Removed duplicate records.
6. Removed rows with missing sentiment or tweet values.
7. Removed unnecessary spaces from text and categorical values.

## 🔍 Exploratory Data Analysis

The dataset was explored to understand:

- The number of tweets in each sentiment category.
- The distribution of positive, negative, neutral, and irrelevant sentiments.
- The most frequently occurring entities.
- Sentiment patterns across different entities.
- Entities with higher numbers of positive and negative tweets.

## 📈 Visualizations

### 1. Sentiment Distribution

A count plot was created to visualize the number of tweets belonging to each sentiment category.

This visualization helps identify which sentiment occurs most frequently in the dataset.

### 2. Sentiment Patterns Across Top 10 Entities

A grouped count plot was created to compare Positive, Negative, Neutral, and Irrelevant sentiments across the top 10 entities.

This visualization helps understand how public opinion differs across different topics or brands.

## 🔍 Key Observations

- The dataset contains tweets associated with different entities.
- The tweets are categorized into Positive, Negative, Neutral, and Irrelevant sentiments.
- The distribution of sentiments shows the overall pattern of public opinion in the dataset.
- Sentiment patterns vary across different entities.
- Some entities have more positive tweets, while others have more negative tweets.
- Visualization makes it easier to identify differences in public sentiment across topics and brands.

## ✅ Conclusion

In this task, Twitter social media data was analyzed to understand sentiment patterns toward different entities.

The dataset was cleaned by removing duplicate and missing records. The distribution of Positive, Negative, Neutral, and Irrelevant sentiments was visualized using a count plot.

Sentiment patterns across the top 10 entities were also analyzed to identify differences in public opinion.

This task provided practical experience in data cleaning, exploratory data analysis, sentiment analysis, and data visualization using Python, Pandas, Matplotlib, and Seaborn.

## 📂 Repository Structure

```text
PRODIGY_DS_04
│
├── Task-04_Sentiment_Analysis.ipynb
└── README.md
