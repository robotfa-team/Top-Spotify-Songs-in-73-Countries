# Top Spotify Songs in 73 Countries

## Overview
This API provides access to the top trending songs in over 70 countries. With a comprehensive dataset of Spotify’s most famous tracks, it delivers insights into song attributes, popularity, and presence across different music platforms. Whether you’re looking to explore music trends, analyze song features, or build data-driven applications, this API offers rich, valuable information for your projects.

### Key Features:
- **Track Information**: Includes track name, artist(s), and release date.
- **Country and Charts**: Provides data segmented by country and chart position.
- **Song Attributes**: Insights into acousticness, danceability, energy level, explicitness, and more.
- **Popularity Metrics**: Access to metrics that showcase song popularity across platforms.

---

## Use Cases and Project Ideas

### 1. Music Trends by Country
Identify the most popular genres of music in different countries over time and uncover cultural preferences.

### 2. Song Ranking Analysis
Analyze how rankings change over time to detect trends and patterns.

### 3. Feature Correlation
Investigate the relationship between song popularity and features like danceability, energy, or explicitness.

### 4. Predictive Analytics
Leverage machine learning to predict future song popularity based on historical data.

### 5. Cultural Comparison
Compare the top songs in various countries to highlight differences in musical tastes.

---

## How to Use This API

### Prerequisites
- A RapidAPI account
- An API token (available through RapidAPI)

### Steps to Get Started


1. **Sign Up on RapidAPI**
   - Visit [RapidAPI](https://rapidapi.com/robotfa-robotfa-default/api/top-spotify-songs-in-73-countries) and create an account if you don’t already have one.

2. **Subscribe to the API**
   - Search for the "Top Spotify Songs in 73 Countries" API and subscribe to it.

3. **Get Your API Token**
   - After subscribing, navigate to the API's "Endpoints" section and copy your unique API token.

4. **Integrate the API**
   - Use the token to authenticate your requests. Here’s a basic example in cURL:
     ```bash
     curl -X GET "https://top-spotify-songs-in-73-countries.p.rapidapi.com/list" \
     -H "X-RapidAPI-Key: YOUR_API_KEY" \
     -H "X-RapidAPI-Host: top-spotify-songs-in-73-countries.p.rapidapi.com"
     ```

---

## Example Endpoints

### 1. Search Songs
Retrieve  songs with many filters:
```bash
GET /list
```


---

## Contribution
If you have suggestions or would like to contribute to this project, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

