# Unemployment Demographic Analysis

## Overview
This project analyzes unemployment rates across different demographic groups in the United States. It utilizes various statistical modeling techniques and data visualization methods to explore trends, disparities, and the impact of policy changes on unemployment.

## Project Structure
The project consists of the following files:

- **analysis.ipynb**: A Jupyter notebook containing the code and analysis for the unemployment demographic analysis. It includes data visualization, statistical modeling, and various analyses related to unemployment rates across different demographic groups.

- **README.md**: This documentation file provides an overview of the project, instructions on how to run the analysis, and any necessary background information.

- **requirements.txt**: A file listing the Python packages required to run the Jupyter notebook. It specifies the dependencies that need to be installed in the Python environment.

- **data/**: This directory contains the following data files:
  - **monthly.csv**: A CSV file containing the monthly unemployment rate data used in the analysis, structured with date and unemployment rate columns.
  - **README.txt**: A file providing information about the data files in the `data` directory, including descriptions of the datasets and any relevant notes.
  - **us_presidents_since_2004.csv**: A CSV file containing data on U.S. presidents since 2004, which may be used to analyze the impact of presidential terms on unemployment rates.

- **docs/**: This directory contains the following documentation file:
  - **Policy_Changes_Unemployment_Summary.txt**: A text file summarizing policy changes related to unemployment, providing context for the analysis in the notebook.

## Instructions
1. **Setup Environment**: Ensure you have Python installed. Create a virtual environment and activate it.
2. **Install Dependencies**: Run the following command to install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. **Run the Analysis**: Open the `analysis.ipynb` notebook in Jupyter Notebook or JupyterLab and execute the cells to perform the analysis.

## Additional Notes
- Ensure that the data files are correctly placed in the `data` directory for the analysis to run smoothly.
- The project can be extended by integrating additional datasets or enhancing the analysis with more advanced statistical techniques.

## Packaging
To package this project for upload to GitHub or embedding on a website, follow these steps:
1. Create a folder named `unemployment-demographic-analysis` and place all the files inside it.
2. Inside the `unemployment-demographic-analysis` folder, create two subfolders: `data` and `docs`, and move the respective folders into them.
3. Compress the `unemployment-demographic-analysis` folder into a zip file for easy upload.