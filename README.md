# YouTube Web Scraper using Python

This project demonstrates a YouTube web scraper built with Python, utilizing the YouTube Data API and Pandas library. The scraper allows you to fetch data from YouTube based on a specific search query and store it in a CSV file for further analysis.

## Prerequisites

- Python 3.x
- Google Cloud Console project with YouTube Data API enabled
- API key for YouTube Data API
- Required Python libraries: `google-api-python-client`, `pandas`

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
   ```

2. Install the required libraries:

   ```bash
   pip install google-api-python-client pandas
   ```

3. Obtain an API key from the Google Cloud Console for the YouTube Data API.

4. Update the `api_key` variable in the Python script with your API key:

   ```python
   api_key = "YOUR_API_KEY"
   ```

## Usage

1. Customize the search query in the Python script:

   ```python
   search_query = "python programming"
   ```

2. Run the Python script:

   ```bash
   python youtube_scraper.py
   ```

3. The script will fetch YouTube data based on the search query and save it to a CSV file named `youtube_videos.csv`.

## Contributing

Contributions are welcome! If you have any ideas, enhancements, or bug fixes, please open an issue or submit a pull request.

## Author

[@prajesh](https://bit.ly/prajesheleven)
