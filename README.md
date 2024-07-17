# Google-Search-Analysis-with-Python

## Introduction 
This script utilizes the Google Trends API to analyze and visualize trends for a user-specified keyword. Upon entering a keyword, the script fetches data on its regional interest and historical search volume, generating two informative charts.

## Brief Explanation

### User Input:
Users input a keyword to search trends for.

### Google Trends API:
The script utilizes pytrends to construct a payload for the specified keyword.

### Data Fetching with Retry Mechanism:
To manage rate limits, the script includes a retry mechanism with a delay between attempts for data retrieval.
Fetches regional interest data and historical search volume.

### Data Visualization:
Plots the top 10 regions by interest in the keyword using a bar chart.
Displays the trend of search volume over time with a line chart.

### Plot Display:
Utilizes matplotlib for both charts, ensuring a clean visual style.
This approach ensures graceful handling of rate limits while providing insightful visualizations of Google search trends for any keyword.
