# Pickle to CSV Converter

## Description
A simple tool for converting .pkl data files into .csv format

## Requirements
- Python 3.x
- Pandas library

## Installation

First, ensure you have Python installed on your system. You can download Python from [https://www.python.org/downloads/](https://www.python.org/downloads/).

Next, clone this repository to your local machine using Git:

```bash
git clone https://github.com/snedev/pickle-to-csv
cd pickle-to-csv-converter
```

Finally, install the required Python libraries using pip:

```bash
pip install -r requirements.txt
```

## Usage
To convert a Pickle file to a CSV file, run the pickle_to_csv.py script from the command line, specifying the path to the input Pickle file and the desired output CSV file path as arguments.

```bash
python pickle_to_csv.py <input_pickle_file_path> <output_csv_file_path>
```

For example:

```bash
python pickle_to_csv.py ./data/orders.pkl ./data/orders.csv
```

This will read the Pickle file located at ./data/orders.pkl and create a new CSV file with the converted data at ./data/orders.csv.