# Myntra Fashion Sense

Myntra Fashion Sense is a web scraping and analysis project that extracts product reviews from Myntra, stores them in MongoDB, and provides insights through a Streamlit-based user interface.

## Video Demo

Here's a video demo of the project:

https://github.com/user-attachments/assets/e4c7b815-1e64-4cb7-a8df-0a9858947bb0

## Features

- Scrape product reviews from Myntra
- Store scraped data in MongoDB and local CSV file
- Analyze reviews for sentiment and trends
- User-friendly Streamlit interface for product search and review analysis
- Customizable number of products to scrape

## Project Structure

The project consists of two main components:

1. **ScrapeReviews**: Handles the web scraping process
2. **DashboardGenerator**: Manages data analysis and visualization

### ScrapeReviews Code Flow

![ScrapeReviews Code Flow](https://github.com/thatritikpatel/myntra_fashion_sense/blob/main/scrape%20code%20flow.png)

### Dashboard Generation Process

![Dashboard Generation Process](https://github.com/thatritikpatel/myntra_fashion_sense/blob/main/generate%20data%20report.png)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/thatritikpatel/myntra_fashion_sense.git
   cd myntra_fashion_sense
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Start the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Use the interface to search for products and specify the number of reviews to scrape.

3. View the analysis results in the Streamlit dashboard.

## Dependencies

- bs4==0.0.1
- chromedriver-binary==121.0.6115.2.0
- database-connect==0.1.66
- flask-cors==4.0.0
- gunicorn==21.2.0
- ipykernel==6.26.0
- plotly==5.18.0
- pysocks==1.7.1
- python-dotenv==1.0.1
- selenium==4.15.2
- streamlit==1.28.0
- tiktoken==0.4.0

## Data Storage

- Scraped data is stored in MongoDB, with a separate collection for each product.
- A local `data.csv` file is also created with the scraped reviews.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Author
- [Ritik Patel](mailto:ritik.patel129@gmail.com)