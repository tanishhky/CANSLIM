# CANSLIM Screening Strategy

An automated quantitative implementation of the C-A-N-S-L-I-M investment paradigm developed by William O'Neil. 

![CANSLIM Screener Results]([Insert Image/Result Here])

## Overview

CANSLIM is a prominent techno-fundamental strategy that identifies high-growth stocks before they make significant price advances. This repository provides a computational pipeline that screens equities against the CANSLIM criteria using historical price data, earnings reports, and market sentiment metrics.

### The Criteria:
- **C**urrent Quarterly Earnings
- **A**nnual Earnings Growth
- **N**ew Products, Management, or Price Highs
- **S**upply and Demand
- **L**eader or Laggard
- **I**nstitutional Sponsorship
- **M**arket Direction

## Repository Contents

- `CANSLIM Main.ipynb`: The primary notebook driving the screening logic, data ingestion, and factor calculation.
- `main.ipynb`: Exploratory data analysis and secondary implementations.
- `*_earnings.csv` & `*.csv`: Ingested datasets including earnings growth, supply/demand data, and market direction over rolling periods.

## Usage
1. Provide the specific structural data CSVs for the evaluated equities.
2. Run the `CANSLIM Main.ipynb` notebook to execute the screening criteria and generate the final candidate list.
