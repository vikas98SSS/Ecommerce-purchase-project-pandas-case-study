# vikas dhakad
# Ecommerce-purchase-project-pandas-case-study


- **File Overview**
  - The file is a Jupyter Notebook that analyzes a dataset of ecommerce purchases.
  - The dataset contains 10,000 rows and 14 columns, including various attributes related to customer purchases.

- **Data Import and Initial Exploration**
  - The dataset is imported using Pandas.
  - The first 10 rows and the last 10 rows of the dataset are displayed to understand its structure and content.

- **Data Structure**
  - The dataset consists of the following columns:
    - Address
    - Lot
    - AM or PM (indicating the time of purchase)
    - Browser Info
    - Company
    - Credit Card
    - CC Exp Date (credit card expiration date)
    - CC Security Code
    - CC Provider (credit card provider)
    - Email
    - Job
    - IP Address
    - Language
    - Purchase Price

- **Data Types and Null Values**
  - The data types of each column are checked, revealing a mix of object, int64, and float64 types.
  - There are no null values in any of the columns.

- **Dataset Characteristics**
  - The dataset contains 10,000 entries and 14 columns.
  - The highest purchase price is $99.99, while the lowest is $0.00.
  - The average purchase price is approximately $50.35.

- **Language and Job Analysis**
  - The number of people who speak French (language code "fr") is 1,097.
  - The number of job titles containing "Engineer" is 984.

- **Email and Credit Card Analysis**
  - The email of the person with the IP address "132.207.160.22" is found.
  - The number of people using Mastercard as their credit card provider and making purchases above $50 is 405.
  - The email of the person with the credit card number "4664825258997302" is also retrieved.

- **Purchase Timing Analysis**
  - The number of purchases made during AM is 4,932, while PM purchases total 5,068.
  - The number of people with credit cards expiring in 2020 is 988.

- **Email Provider Popularity**
  - The top 5 most popular email providers are identified:
    - hotmail.com: 1,638 users
    - yahoo.com: 1,616 users
    - gmail.com: 1,605 users
    - smith.com: 42 users
    - williams.com: 37 users

