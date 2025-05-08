# BeautifulSoup Fundamentals

This repository contains a beginner-friendly web scraping project using Python’s BeautifulSoup library. It scrapes book data from [Books to Scrape](http://books.toscrape.com/) and shows how to extract structured information from web pages.

## 📘 Project Overview

This project performs the following:

- Scrapes book title, price, availability, and star rating
- Handles single-page and multi-page (first 3 pages) scraping
- Saves data into CSV files using pandas
- Implements basic rate limiting
- Logs scraping activity and errors
- Generates a summary of the scraped data
---
## ✅ Tasks Overview

### Task 1: Basic Book Scraping

- Scrape the **first page** of books
- Extract:
  - Title
  - Price
  - Availability
  - Star rating
- Save to `books_basic.csv`
---
### Task 2: Multi-page Scraping

- Scrape the **first 3 pages**
- Use `time.sleep()` for basic rate limiting
- Save to `books_multipage.csv`
---
### Additional Features

- **Logging**: Logs major events and errors to `scraping_log.log`
- **Documentation**: Code includes comments and docstrings
- **Summary**: Generates:
  - Total number of books
  - Availability count
  - Star rating distribution
  - Average price
---
## 💻 Tech Stack
- Python
- BeautifulSoup
- Requests
- Pandas
- Logging
- Time
---
## 📁 File Structure

BeautifulSoup-Fundamentals/
│
├── books_basic.csv # Data from Task 1
├── books_multipage.csv # Data from Task 2
├── scraping_log.log # Log file
├── books_yourname_youremail.py # Main script
└── README.md # Project documentation
---

## 🧪 How to Run

1. **Clone the repo**
```bash
git clone https://github.com/osamanoor17/BeautifulSoup-Fundamentals.git
cd BeautifulSoup-Fundamentals
```
2. **Install dependencies**
pip install requests beautifulsoup4 pandas

3. **Run the script**
python books_mosamanoor17@gmail.com.py

## 📌 Notes ## 
Uses Books to Scrape for educational purposes
Pagination limited to 3 pages for simplicity
No external database or API is used
