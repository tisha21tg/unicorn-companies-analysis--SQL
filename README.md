# SQL---Analyzing-Unicorn-Companies
Analyzing Unicorn Companies Using SQL in Jupyter Notebook

![alt text](https://github.com/Ahmed-R-Hamdan/SQL---Analyzing-Unicorn-Companies/blob/main/image/unicorn.jpg)

This project aims at exploring the below points:


- Three best-performing industries based on the number of new unicorns created over the last three years (2019, 2020, and 2021) combined.?
- Unicorn companines over continent during the last three years (2019, 2020, and 2021) combined
- What is the first unicorn company?
- Check number of companies over years.
- Get percentage of unicorn companies at 2021 to the total
- Check the industry category of companies at 2021
- How many years it take to join to unicorn club?


## Datasets

Datasets folder contains the following files to create database tables:

`dates`

| Column         | Description                                     |
|-------------   |------------------------------------------------ |
| `company_id`   | A unique ID for the company.                    |
| `date_joined`  | The date that the company became a unicorn.     |
| `year_founded` | The year that the company was founded.          |

`funding`

| Column           | Description                                  |
|----------------- |--------------------------------------------- |
| company_id       | A unique ID for the company.                 |
| valuation        | Company value in US dollars.                 |
| funding          | The amount of funding raised in US dollars.  |
| select_investors | A list of key investors in the company.      |

`industries`

| Column       | Description                                  |
|------------- |--------------------------------------------- |
| company_id   | A unique ID for the company.                 |
| industry     | The industry that the company operates in.   |

`companies`

| Column       | Description                                       |
|------------- |-------------------------------------------------- |
| company_id   | A unique ID for the company.                      |
| company      | The name of the company.                          |
| city         | The city where the company is headquartered.      |
| country      | The country where the company is headquartered.   |
| continent    | The continent where the company is headquartered. |
