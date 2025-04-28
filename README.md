# YouTube-Video-Performance-Analysis-for-Netflix-India
# YouTube Video Performance Analysis for Netflix India

## Project Overview

This project involves analyzing the performance of YouTube videos related to Netflix India. The dataset contains various metadata such as video ID, title, description, tags, view count, like count, comment count, published date, and video duration. The goal of this analysis is to identify trends, patterns, and actionable insights that Netflix India can use to optimize their YouTube content strategy.

## Dataset

The dataset used for this analysis consists of the following key columns:

- **Video ID**: A unique identifier for each YouTube video.
- **Title**: The title of the video.
- **Description**: A brief explanation of the video content.
- **Tags**: Keywords that categorize the video content.
- **Published Date**: The timestamp when the video was published on YouTube.
- **View Count**: The number of times the video has been viewed.
- **Like Count**: The number of likes the video has received.
- **Comment Count**: The number of comments the video has garnered.
- **Duration**: The length of the video in ISO 8601 format (e.g., PT26M12S).

## Project Approach

### 1. Data Cleaning
The first step involved cleaning the data by handling missing or invalid values, checking for duplicates, and ensuring that the dataset was ready for analysis.

### 2. Exploratory Data Analysis (EDA)
In this phase, we explored the data to understand trends and relationships between key variables like view count, like count, comment count, and video duration. We also visualized these relationships using various charts and graphs.

### 3. Insights and Analysis
We explored several questions to gain insights into the performance of the videos:

- Does the duration of the video influence views and comments?
- Is there a relationship between views and comments?
- Do certain tags help videos achieve more views?
- Does the time of video publishing (day or hour) influence engagement?
- What type of content (based on tags) performs better?

### 4. Actionable Recommendations
Based on the analysis, actionable recommendations were made to help Netflix India optimize their YouTube strategy for greater audience engagement.

---

## Key Findings

- **Duration**: Shorter videos (less than 5 minutes) generally had higher engagement, including more views, likes, and comments.
- **Tags**: Videos with specific tags related to Netflix Originals and popular genres saw higher views.
- **Publishing Time**: Videos published during weekdays had better engagement than those published on weekends.
- **Title Length**: Videos with more concise and catchy titles tended to perform better in terms of views and interactions.

---

## Actionable Insights

1. **Focus on Shorter Videos**: Create content with a duration of 5 minutes or less to maximize viewer engagement.
2. **Use Specific Tags**: Ensure videos are tagged with trending and relevant keywords, such as "Netflix Original" and popular show titles.
3. **Post During Weekdays**: Publish videos on weekdays to optimize engagement.
4. **Optimize Titles**: Craft shorter, more engaging titles to attract viewers.

---

## Technologies Used

- **Python**: Used for data cleaning, analysis, and visualization.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib / Seaborn**: For visualizing the data.
- **Jupyter Notebooks**: For creating and presenting the analysis.

---

## Conclusion

This analysis has provided Netflix India with valuable insights into the performance drivers behind their YouTube videos. By understanding the relationship between video attributes (such as duration, tags, publishing time) and audience engagement, Netflix India can make data-driven decisions to optimize their content strategy and reach a larger audience.

Future work could include further refinement of the dataset, additional feature engineering, or deeper exploration of audience demographics to provide even more granular insights.

---

## Installation and Setup

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/netflix-india-yt-analysis.git
