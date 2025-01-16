# Toronto Traffic Collisions EDA Project

This project performs an Exploratory Data Analysis (EDA) on traffic collisions in Toronto using data from the Toronto Open Data Portal. The goal is to gain insights into collision trends, identify potential hotspots, and explore temporal and spatial patterns to better understand road safety issues in Toronto.

**Dataset Name:** [Police Annual Statistical Report - Traffic Collisions](https://open.toronto.ca/dataset/police-annual-statistical-report-traffic-collisions/)

**Data Source:** Toronto Open Data Portal

**File Format:** CSV

<br>

## Project Structure

The project directory is organized as follows:

```
├── data/               # Folder for raw and processed datasets (not uploaded due to size restrictions)
├── notebooks/          # Jupyter notebooks for EDA and visualizations
├── outputs/            # Folder for figures, plots, and summary tables
├── README.md           # Project documentation
├── requirements.txt    # Python dependencies for the virtual environment
└── .gitignore          # Specifies files and folders to be ignored by Git
```

## Installation and Setup

**1. Clone the Repository**

To get a copy of this project locally, use the following command:

```bash
git clone https://github.com/raghadkibrahim/toronto-collisions-eda.git
cd toronto-collisions-eda
```

**2. Set Up the Virtual Environment**

Create and activate a virtual environment to isolate dependencies:

- Mac/Linux:

```bash
python -m venv venv
source venv/bin/activate
```

- Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

**3. Install Dependencies**

Install the required packages listed in requirements.txt:

```bash
pip install -r requirements.txt
```

**4. Launch Jupyter Notebook**

Navigate to the notebooks/ folder and start Jupyter Notebook:

```bash
cd notebooks
jupyter notebook
```
