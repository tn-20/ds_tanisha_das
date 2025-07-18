## Data Science Assignment – Primetrade.ai

This project explores how trading behavior changes with market sentiment (Fear vs Greed) using historical trader data and Bitcoin sentiment index.

## Folder Structure

ds_tanisha_das/
├── notebook_1.ipynb # Main Google Colab notebook with code
├── csv_files/
│ ├── trader_data.csv # Raw trader data
│ ├── sentiment_data.csv # Sentiment dataset (Fear/Greed)
│ └── merged_data.csv # Cleaned and merged dataset
├── outputs/
│ ├── pnl_sentiment.png # PnL distribution by sentiment
│ ├── roi_sentiment.png # ROI variation by sentiment
│ └── correlation.png # Feature correlation heatmap
├── ds_report.pdf # Summary of insights and strategy suggestions
└── README.md # This file

## Objective

To analyze how trader performance (PnL, ROI, volume) varies across different market sentiment regimes, and to identify top-performing traders based on sentiment-driven behavior.

## Overview

- Cleaned and merged trader and sentiment datasets using date
- Created an ROI (Return on Investment) metric
- Performed exploratory data analysis using Seaborn and Matplotlib
- Ranked traders under Fear and Greed based on ROI and PnL
- Summarized insights in a PDF report

## Key Metrics Used

- Closed PnL (Profit or Loss)
- ROI = PnL ÷ (Execution Price × Trade Size)
- Trade Volume (Size Tokens)
- Sentiment (Fear, Greed, Extreme Fear)

## Tools Used

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Google Colab
- GitHub

## Deliverables

- `notebook_1.ipynb`: All analysis and code
- `outputs/`: Visual charts from analysis
- `ds_report.pdf`: Final summary report
- `README.md`: This project description file

## Data Files (Hosted on Google Drive due to size limits)

- [trader_data.csv]([https://drive.google.com/your-link-here](https://drive.google.com/file/d/162CMrg6vvulPutxNpLxRvyZWTjKuomHF/view?usp=sharing))
- [merged_data.csv]([https://drive.google.com/your-other-link-here](https://docs.google.com/spreadsheets/d/1aSvA7JfeFZdV_7KunIqU5iCryS8Zr9WMbLL7a7c-FRY/edit?usp=drive_link))

## How to Run

1. Open `notebook_1.ipynb` in Google Colab
2. Mount Google Drive when prompted
3. Ensure all CSV files are in `csv_files/`
4. Run the notebook cells in order

## Author

Tanisha Das  
