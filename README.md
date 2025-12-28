# Airbnb Price, Preferences, and Rating Analytics Dashboard

[![Python Version](https://img.shields.io/badge/Python-3.9+-3776AB.svg?style=flat\&logo=python)](https://www.python.org/)
[![Frameworks](https://img.shields.io/badge/Frameworks-Pandas%2C%20Plotly%2C%20Looker%20Studio-purple.svg)](#)
[![Dashboard](https://img.shields.io/badge/Dashboard-Live%20Access-blue.svg)](https://lookerstudio.google.com/reporting/59cd02a5-9c00-465e-8832-565dac65b9f6)

**This project is developed as part of the Dashboard Visualization Competition at GELAR RASA 2024.**

## Project Overview

This repository contains a complete data analysis and visualization workflow for an **Airbnb analytics dashboard**, developed for the **GELAR RASA 2024 Dashboard Visualization Competition**.

The project focuses on extracting insights from Airbnb listing data to analyze:

* Pricing patterns across districts and property types
* User preferences and listing popularity
* Factors influencing listing prices
* Relationship between price and customer ratings
* Optimal price estimation based on listing attributes

The final deliverable is an **interactive Looker Studio dashboard** designed for data storytelling and insight-driven decision making.

## Live Dashboard

The finalized dashboard can be accessed here:

[https://lookerstudio.google.com/reporting/59cd02a5-9c00-465e-8832-565dac65b9f6](https://lookerstudio.google.com/reporting/59cd02a5-9c00-465e-8832-565dac65b9f6)


## Dataset Information

### Study Case Data (Official Competition Dataset)

The `study case/` directory contains **raw datasets provided directly by the GELAR RASA 2024 competition organizers** and serves as the primary data source for this project.

Contents include:

* `listings.csv` – Airbnb listing details
* `reviews.csv` – Customer review data
* `hosts.csv` – Host information
* `data_dictionary.txt` – Dataset description and feature definitions
* `Study Case DA.pdf` – Official competition case brief

These files are **not modified** and are preserved as the original reference data.

## Processed & Derived Data

Additional datasets generated during analysis and feature engineering are stored in:

* `data/` – Intermediate cleaned datasets in CSV and XLSX formats
* `results/` – Final analytical outputs such as:

  * Price correlation matrix
  * Amenities count analysis
  * Optimal price estimation results
  * RMSE evaluation table

## Key Features

### Price & Property Analysis

* Average price comparison by property and room type
* Listing price distribution across districts
* Impact of amenities count on pricing

### Preference & Popularity Insights

* Most popular property and room types based on number of reviews
* District-level filtering and comparison

### Ratings & Reviews Analysis

* Average ratings by category (cleanliness, location, communication, etc.)
* Relationship between listing price and review scores
* Top listings based on overall ratings

### Price Optimization

* Optimal price estimation based on:

  * Property type
  * Room type
  * Location
  * Number of bedrooms
  * Guest capacity
  * Amenities availability

## Project Structure

```
GELAR RASA 2024/
├── data/
│   ├── dfh.csv
│   ├── dfl.csv
│   ├── dfr.csv
│   ├── *.xlsx
│   └── new data explaination.txt
│
├── notebook/
│   └── GelarRasa2024.ipynb
│
├── results/
│   ├── listing_amenities_count.csv
│   ├── optimal_price.csv
│   ├── optimal_price_combinations_from_model.csv
│   ├── price_correlation_matrix.csv
│   └── tabel_rmse.xlsx
│
├── study case/
│   ├── listings.csv
│   ├── reviews.csv
│   ├── hosts.csv
│   ├── data_dictionary.txt
│   └── Study Case DA.pdf
│
└── README.md
```

## Team Members / Collaborators

* **Aufii Fathin Nabila**
* **Dwi Cahya Maulani**
* **Firza Zaha Iklima**
