# YouTube Data Analysis


This project gathers, analyzes, and visualizes data from YouTube using the YouTube Data API. It helps you understand YouTube channels and their content by fetching channel statistics, retrieving video details, and creating visualizations.

## Features

- **Channel Statistics:** Get information like subscriber count, total views, and video count for multiple YouTube channels.
- **Video Details:** Retrieve details about videos, such as views, likes, comments, and publish date.
- **Data Visualization:** Create bar plots to visualize channel statistics and the top 10 most viewed videos.

## How It Works

1. **Set Up API Key:** Get an API key from the [Google Cloud Console](https://console.cloud.google.com/) and replace the placeholder `api_key` in the notebook with your key.
2. **Specify Channels:** Add the YouTube channel IDs you want to analyze to the `channel_ids` list.
3. **Run the Notebook:** Execute the cells to scrape data, perform analysis, and generate visualizations.

## Dependencies

- `googleapiclient` - For accessing the YouTube Data API.
- `pandas` - For handling and analyzing data.
- `numpy` - For numerical operations.
- `seaborn` - For creating visualizations.

## References

- YouTube Data API: [YouTube Data API Documentation](https://developers.google.com/youtube/v3/docs)
