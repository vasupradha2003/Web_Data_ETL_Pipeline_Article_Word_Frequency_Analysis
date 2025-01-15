# Web Data ETL Pipeline: Article Word Frequency Analysis

This project demonstrates an end-to-end pipeline that extracts text data from a given URL, processes the data, and calculates the frequency of words appearing in the article. The pipeline involves:

- **Web Scraping**: Extracting raw text from a webpage.
- **Text Processing**: Tokenizing the text and removing common stopwords to focus on meaningful words.
- **ETL Pipeline**: Combining extraction and transformation to generate a word frequency table.
- **Data Analysis**: Displaying the most frequent words in the article.

## Features
- Extracts and processes the text from an article URL.
- Cleans and tokenizes the text, removing stopwords.
- Displays the top N frequent words based on user input.
- Provides easy-to-interpret word frequency analysis in tabular format.

## Project Overview
This project is designed to be used as a tool for word frequency analysis of online articles. It is implemented using Python, utilizing popular libraries like:

- **BeautifulSoup**: For scraping the content of a webpage.
- **NLTK**: For text processing (including stopword removal).
- **Pandas**: For organizing the word frequency results.
- **Requests**: For sending HTTP requests to the target URLs.

## Technologies Used:
- Python 3.x
- BeautifulSoup
- NLTK
- Pandas
- Requests

## Usage
To run the project and view the top N frequent words:
- Modify the URL in the script to point to an article of your choice.
- Run the script to extract the article content, clean the text, and analyze the word frequency.
- Use the head() function to display the top N most frequent words (e.g., top 10, top 50, top 100).
  
## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request. 

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- BeautifulSoup: BeautifulSoup Documentation
- NLTK: NLTK Documentation
- Pandas: Pandas Documentation
- Requests: Requests Documentation

