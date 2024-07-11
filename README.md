# E-commerce Data Analysis Project

This project showcases the use of SQL and Python for analyzing an E-commerce dataset. The dataset is processed and queried using MySQL, and the results are visualized using `matplotlib` and `seaborn`.

## Dataset

The dataset is sourced from Kaggle: [E-commerce Dataset](https://www.kaggle.com/datasets/devarajv88/target-dataset?resource=download).

## Project Overview

1. **Download the Dataset**
    - Download and unzip the dataset from Kaggle.

2. **Convert CSV to SQL Dataset**
    - Convert the CSV files into SQL format and load them into a MySQL database using Python.

3. **Run Queries and Analyze Data**
    - Use Python in a Jupyter Notebook to run SQL queries on the MySQL database.
    - Visualize the results using `matplotlib` and `seaborn`.

## Project Setup

### Prerequisites

- Python 3.x
- MySQL Workbench
- Jupyter Notebook
- Required libraries: `pandas`, `mysql-connector-python`, `sqlalchemy`, `matplotlib`, `seaborn`

### Installation

1. **Clone the Repository**

    ```sh
    git clone https://github.com/originalauthor/ecommerce-data-analysis.git
    cd ecommerce-data-analysis
    ```

2. **Install Required Libraries**

    ```sh
    pip install pandas mysql-connector-python sqlalchemy matplotlib seaborn
    ```

3. **Download and Unzip the Dataset**

    Download from [Kaggle](https://www.kaggle.com/datasets/devarajv88/target-dataset?resource=download) and unzip into the project directory.

4. **Set Up MySQL Database**

    - Open MySQL Workbench and create a new database.
    - Use the provided Python script to load CSV data into the MySQL database.

### Running the Analysis

1. **Open Jupyter Notebook**

    ```sh
    jupyter notebook
    ```

2. **Run the Notebook**

    - Open `Ecommerce_Analysis.ipynb`.
    - Run cells to connect to MySQL, load data, execute queries, and visualize results.

## Files in the Repository

- `README.md`: This file.
- `Questions.txt`: Analysis questions.
- `Ecommerce_Analysis.ipynb`: Jupyter Notebook with Python code and visualizations.
- `data/`: Directory for the dataset files.


## Acknowledgments

- Original project and dataset by [Devaraj V](https://www.kaggle.com/devarajv88) on Kaggle.
