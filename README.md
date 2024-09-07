# Price Analysis and Stochastic Oscillator on Kraken

This project was created by Paula Sanjuan Campos and Inés Hernández Pastor, students of the Master's in Big Data Science at the University of Navarra. The main objective is to download and visualize price quotes for a currency pair using Python and Streamlit.


## Tools Used

### 1. Python

### 2. Kraken API

The Kraken API is used to download up-to-date price quotes.

### 3. Streamlit 

The user interface has been created with Streamlit, a Python library that facilitates the creation of interactive web applications. In our case, users can select a cryptocurrency pair from six possible options and visualize the quotes and indicators.

### 4. Virtual Environment

We have configured a specific virtual environment for this project using virtualenv. This ensures that the dependencies and versions of the libraries used are consistent, avoiding potential conflicts with other projects.



## Setup Instructions

### 1. Download from GitHub

There are two ways to obtain the code from GitHub:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ihernandezp1/Proyecto_final_python_PaulaSanjuan_InesHernandez 
   cd your_project

2. **Download the .zip file**

    Extract the files from the compressed folder
    'Proyecto_final_python_PaulaSanjuan_InesHernandez-main'. Navigate to the project folder from the terminal and configure the virtual environment as indicated in the next section.


2. Configure and Activate the Virtual Environment

    ```
    # create the virtual environment
    virtualenv venv
    # activation
    # For MacOs: 
    source venv/bin/activate
    # For Windows:
    venv/Scripts/activate
3. Install dependencies

    ```
    pip install -r requirements.txt
    streamlit run main.py
## Main Features

### User Interface

On the left side of the page that opens in the browser, you will find the Main Menu, which includes the index to select the tab you want to view:  'Introduction', 'Prices', or 'Indicators'.

### 1. Downloading Price Data
The project allows you to download up-to-date price data from the Kraken platform for the currency pair selected by the user. The downloaded data will serve as the basis for further analysis.

In the 'Prices' view, you can select the pair to be represented.

### 2. Price Movement Charts
Once the price data has been downloaded, users can easily visualize the historical movement of the currency pair through a candlestick chart. This graphical representation will help identify patterns and trends in price behavior.

In the same 'Prices' view, once the pair is selected, you will see the candlestick chart, and below it, the DataFrame on which the representation is based.

### 3. Stochastic Oscillator
Additionally, the project includes the generation of charts for the stochastic oscillator, a widely used technical indicator in stock analysis. This tool provides signals on potential overbought or oversold conditions of the currency pair, helping to make informed decisions.

In the 'Indicators' view, users select the currency pair again to visualize the price data (closing price over time), the stochastic indicator, and the moving average of the stochastic. Additionally, a combined graph of these indicators is shown for simultaneous visualization. Finally, the price data is plotted over its moving average.



