# Market Intelligence: Automotive Industry Analysis

## Business Context
Understanding market trends and consumer sentiment is essential for strategic sourcing and category management. This project demonstrates **automated data collection and unstructured text analysis** to extract actionable insights from online discussions—skills directly applicable to supplier intelligence, market research, and competitive analysis in procurement.

## Project Highlights

### Problem Addressed
Built an **automated market intelligence pipeline** to analyze consumer preferences in the entry-level luxury sedan market by:
- Scraping 5,000+ forum posts from Edmunds.com
- Extracting structured data from unstructured discussions
- Preparing data for sentiment and topic analysis

### Key Outcomes
- **Scalable Data Collection**: Automated scraper handling dynamic web content and pagination
- **Structured Dataset**: Clean, analysis-ready data with user IDs, timestamps, and comment text
- **Market Coverage**: Comprehensive capture of consumer opinions on competing brands
- **NLP-Ready Output**: Preprocessed text suitable for downstream sentiment and topic modeling

## Methodology
1. **Web Scraping**: Selenium-based automation for JavaScript-rendered content
2. **Data Extraction**: Parsing HTML to extract structured fields
3. **Data Cleaning**: Standardizing formats, handling missing values
4. **Export**: CSV output for analysis in Python/R

## Technologies
| Category | Tools |
|----------|-------|
| Web Scraping | Selenium, BeautifulSoup |
| Automation | Webdriver-Manager, Chromium |
| Data Processing | Pandas |
| Language | Python |

## How to Run
```bash
pip install selenium beautifulsoup4 pandas webdriver-manager
jupyter notebook Scraping.ipynb
```

## Skills Demonstrated
- **Market Research** - Competitive intelligence, consumer sentiment collection
- **Web Scraping** - Dynamic content extraction, browser automation
- **Data Engineering** - ETL pipelines, data cleaning, structured output
- **Python Automation** - Scripting, error handling, scalable data collection
- **Unstructured Data** - Text extraction, preprocessing for NLP

