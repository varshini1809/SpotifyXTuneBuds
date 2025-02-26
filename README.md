# D Project Spotify X Tune Buds Business Analysis

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Data Description](#data-description)
4. [Analysis and Methodology](#analysis-and-methodology)
5. [Results and Insights](#results-and-insights)
6. [Installation and Usage](#installation-and-usage)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact Information](#contact-information)

## Introduction
Hack Ltd is an electronic consumer goods manufacturer. This season, we are collaborating with Spotify to launch a Christmas limited edition of our earbuds, called Hack Buds. Using insights from Spotify's October 2022 Top Tracks dataset, we will feature a top artist in a joint-marketing campaign. Hack Buds will combine festive designs with premium audio quality, offering a unique holiday gift for music lovers.

## Project Overview
The analysis covers Top Tracks with popularity > 90 focusing on the music features and genres, as well the most popular artist from last month. The main objective is to provide actionable insights for marketing department and product center.

## Data Description
The dataset includes:
- Top Tracks on Spotify in October 2022.
- Variables: `track_id`, `artists`, `album_name`, `track_name`, `popularity`, `duration_ms`, `explicit`, `danceability`, `energy`, `key`, `loudness`, `mode`, `speechiness`, `acousticness`, `instrumentalness`, `liveness`, `valence`, `tempo`, `time_signature`, `track_genre`.
- Data was cleaned to remove duplicates and missing values and map the inconsistancy.
- Data was filtered and pivot to demonstrate the top tracks with popularity > 90 focusing on the music features and genres, along with the top artist with the most counts of top tracks.

## Analysis and Methodology
We used Python for data analysis, leveraging libraries such as pandas, numpy, seaborn, and matplotlib. Key analyses include:
- Descriptive statistics to summarize data.
- Data visualisations to demonstrate the business findings.
- Correlation analysis to find relationships between variables.

## Results and Insights
- There are a total of 24 songs with a popularity score above 90.
- Considering the attributes of those songs, the most fitting genres would be Dance Pop.
- Bad Bunny was considered as the most popular artist last month.
  Recommendations include targeted joint-marketing campaigns with Bad Bunny and the product functionalities are defined based on the music features – Dance Pop.

## Installation and Usage
- Install Python 3.8 or higher.
- Install required libraries: `pip install pandas numpy seaborn matplotlib`.
- Run the analysis script: `Spotify_X_Hackbuds.ipynb`.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License
No license need for this project.

## Contact Information
For any questions, please contact:
- Name: Varshini S
- Email: varshini.18shankar19@gmail.com
