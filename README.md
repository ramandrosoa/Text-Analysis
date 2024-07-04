# [Text Analysis Notebook](text_analysis_1.ipynb)

## Overview
Text analysis encompasses various techniques for extracting meaningful insights from textual data. This project demonstrates sentiment analysis to assess emotional tone and readability analysis using the Gunning Fog Index to measure text complexity.

## Features
- Web scraping for article retrieval: Automatically extracts text from online sources for analysis. ([Link to the article](https://insights.blackcoffer.com/what-if-the-creation-is-taking-over-the-creator/))
- Text cleaning (stopword and punctuation removal): Prepares the text for more accurate analysis by removing irrelevant elements.
- Sentiment analysis
  - Scoring and visualization with word clouds: Provides a visual representation of sentiment in the text.
  - Polarity and subjectivity assessment: Quantifies the overall emotional tone and personal opinion level in the text.
- Readability analysis using the Gunning Fog Index: Evaluates the complexity and accessibility of the text.

## Key Components
1. Article extraction via web scraping: Allows for analysis of current, real-world text data.
2. Stopwords dictionary integration: Improves analysis accuracy by filtering out common, non-informative words.
3. Text cleaning function: Ensures consistency and improves the quality of the analysis.
4. Sentiment analysis with custom dictionaries: Enables tailored sentiment scoring based on specific vocabularies.
5. Readability evaluation using the Gunning Fog Index: Provides a standardized measure of text complexity.
6. Syllable counter for long word identification: Supports the Gunning Fog Index calculation by identifying complex words.

## Importance
This project highlights the significance of text cleaning in sentiment analysis and showcases how readability metrics can enhance text accessibility and ensure compliance with industry standards. It demonstrates the practical application of natural language processing techniques in real-world scenarios.

## Formula
The Gunning Fog Index is calculated as:

$$
Gunning \ Fog \ Index = 0.4 * (Average \ sentence \ length + Percentage \ of \ long \ words)
$$

This formula provides a numerical representation of text complexity, considering both sentence structure and vocabulary difficulty.

## Technologies Used
- NLTK: A leading platform for building Python programs to work with human language data.
- spaCy: An open-source software library for advanced natural language processing.
- [Custom dictionaries for sentiment analysis](https://github.com/ramandrosoa/Text_Analysis/tree/main/DICT): Allows for domain-specific sentiment scoring.

This project combines various text analysis techniques to provide a comprehensive understanding of textual content, from emotional tone to readability.
