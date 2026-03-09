# Demographic Data Analyzer

A Python project built as part of the **FreeCodeCamp Data Analysis with Python** certification.

## Description
Analyzes demographic data extracted from the **1994 Census database** using Pandas.
The `calculate_demographic_data()` function answers 9 key demographic questions
from the dataset covering race, age, education, income, work hours, and country.

## Questions Answered
1. How many people of each race are represented in the dataset?
2. What is the average age of men?
3. What percentage of people have a Bachelor's degree?
4. What percentage of people with advanced education (Bachelors, Masters, Doctorate) earn >50K?
5. What percentage of people without advanced education earn >50K?
6. What is the minimum number of hours a person works per week?
7. What percentage of people who work minimum hours earn >50K?
8. Which country has the highest percentage of people earning >50K?
9. What is the most popular occupation for people earning >50K in India?

## How to Run
```bash
python main.py
```

## Project Structure
├── demographic_data_analyzer.py  # Main solution file
├── adult.data.csv                # Dataset (1994 Census)
├── main.py                       # Run and test the solution
├── test_module.py                # Unit tests (do not modify)
└── README.md

## Technologies Used
    Python 3

    Pandas

## Dataset Source
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository.
Irvine, CA: University of California, School of Information and Computer Science.
http://archive.ics.uci.edu/ml
