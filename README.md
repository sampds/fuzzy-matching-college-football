# College Football Coach Salary Recommendations

## Description

This was a key deliverable in IST 718, Big Data Analytics. It demonstrates an advanced level of data manipulation and analysis, involving a series of complex tasks, including scraping and fuzzy matching to link records. The resulting dataset was used to model the salaries of college coaches.

### Motivation

I was driven to match as many records as I could, as the challenge of uniting data from disparate sources was exciting to solve.

### Problems Addressed

The main issues I focused on were employing fuzzy matching to combine records that refer to college football teams by multiple names, as well as to select the variables used for modeling.

### Learning Experience

The project highlighted the importance of meticulous data cleaning and preparation in data analysis. I also gained practical experience in using advanced Python libraries for data processing tasks.

## Impact and Results

- Overcame the challenge of integrating data from diverse sources, ensuring consistency and accuracy.
- Created model that predicted Syracuse coach's salary within 3.5%.

## Installation

To set up the development environment, follow these steps:

1. Clone the repository to your local machine.
2. Install the libraries from the script. For specifics about versions and dependencies, see the requirements.txt file.
3. Change the filepaths of datasets to match your machine's filepaths.

## Usage

You can use the main dataset and skip to the modeling section, or you can walk through the cleaning process with the raw datasets first.

### Scraping and Preprocessing 

Utilize libraries including requests, lxml.html, and pandas for data scraping and preprocessing.

##Fuzzy Matching Functions

Employ fuzzy matching techniques to identify and correct mismatches in data. This included the use of the libraries thefuzz and Levenshtein for efficient string matching.

## Exploratory Data Analysis 

Conduct an in-depth exploratory analysis to uncover insights from the data, ultimately focusing on choosing variables to include in model.

## Modeling
Created 9 different linear models to recommend college coach salaries, and select the best-performing model.

## Future Development

I would like to further improve the fuzzy matching functions I wrote.