# Stock Market Analyzer

## Description

This project is a **Stock Market Analyzer** built using Python. It focuses on analyzing stock data, performing statistical analysis, and utilizing various visualization techniques to uncover market trends and patterns.

## Features

- **Data Pre-processing**: Cleans and formats stock data for analysis.
- **Statistical Analysis**:
    - Candlestick Charts
    - Rangeslider Plot
    - Volume Analysis
    - Daily Returns & Volatility
    - Correlation Heatmaps
- **Technical Indicators**:
    - Moving Average Convergence Divergence (MACD)
    - Relative Strength Index (RSI)
    - Stochastic Oscillator
    - Bollinger Bands
    - Average Directional Index (ADX)
- **Visualization**: Uses `plotly` and `seaborn` for interactive charts.

## Dataset

The project uses stock data for three companies:

- **Tata Motors** (`Tata.csv`)
- **Maruti Suzuki** (`Maruti.csv`)
- **Mahindra & Mahindra** (`MandM.csv`)

The data covers the period from **20-Nov-2023 to 14-Nov-2024**, downloaded from the **NSE website**.

## Installation

### Prerequisites

Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

### Steps

1. **Clone the Repository**
    
    ```bash
    git clone https://github.com/niyatipatel2005/Stock-Market-Analysis.git
    cd Stock-Market-Analysis
    ```
    
2. **Create a Virtual Environment** (optional but recommended)
    
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
    
3. **Install Dependencies**
    
    ```bash
    pip install -r requirements.txt
    ```
    
4. **Run the Analysis**
    
    ```bash
    python main.py
    ```
    

## Project Structure

```
stock-market-analyzer/
│── cleaned_files/
│   ├── MandM.csv
│   ├── Maruti.csv
│   ├── Tata.csv
│── .gitignore
│── MandM.csv
│── Maruti.csv
│── Tata.csv
│── stock_market_analysis.ipynb
│── Master_file_DAV.pdf
│── requirements.txt
│── README.md
```

## Dependencies

- **pandas**: Data processing and analysis.
- **numpy**: Numerical computations.
- **plotly**: Interactive visualization.
- **seaborn**: Statistical data visualization.
- **ta**: Technical analysis indicators.

## Usage

- Modify `main.py` to analyze different stocks.
- Run the script to generate visualizations and statistical insights.

## License

This project is licensed under the MIT License.

## Author

Developed by [Niyati Patel](https://github.com/niyatipatel2005).
