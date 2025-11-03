# Electricity Trading Strategy

## Overview
Aim: To analyze intraday electricity price data in the Great Britain (GB) electricity market over a recent week (01/09/2024 - 08/09/2024). The goal is to identify volatility patterns and propose a simple trading strategy to capitalize on these patterns.

This repository contains a trading strategy designed to capitalize on price discrepancies between intraday and day-ahead electricity prices in the UK market. The strategy utilizes moving averages, volume data, and historical price patterns to generate buy and sell signals.

## Data Sources
1. Intraday (half-hourly): [Elexon](https://bmrs.elexon.co.uk/api-documentation/endpoint/balancing/pricing/market-index) | Used API end-points to fetch data. 	
2. day-ahead (hourly): [entsoe](https://transparency.entsoe.eu/transmission-domain/r2/dayAheadPrices/show?name=&defaultValue=false&viewType=TABLE&areaType=BZN&atch=false&dateTime.dateTime=01.09.2024+00:00|CET|DAY&biddingZone.values=CTY|10Y1001A1001A92E!BZN|10Y1001A1001A59C&resolution.values=PT60M&dateTime.timezone=CET_CEST&dateTime.timezone_input=CET+(UTC+1)+/+CEST+(UTC+2)) | Manually downloaded CSV files. 

## Features

- **Data Analysis**: Analyze historical electricity prices to identify periods of high and low volatility.
- **Trading Strategy**: Implement a systematic approach to trading based on moving averages and volume thresholds.
- **Profitability Calculation**: Simulate trades to estimate potential profitability based on historical data.
- **Visualization**: Plot intraday prices, day-ahead prices, moving averages, and trading signals for better insights.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries:
  - pandas
  - matplotlib
  - numpy

### Installation

1. Clone the repository:
   ```bash
   https://github.com/omm-prakash/Great-Britain-Energy-Trading-Strategy.git
   cd Great-Britain-Energy-Trading-Strategy

  

### Usage
Load your electricity price data into the script.
Run the `main.ipynb` script to analyze data, generate signals, and visualize results. 


Feel free to let me know if you need further clarification @ommprakash2568@gmail.com!


