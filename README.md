# IoT Log Parser

This project parses IoT logs for Smart City applications. It extracts data, handles errors, and provides visualizations.

## Features
- Extracts key-value pairs, JSON, and Base64 images.
- Handles errors gracefully and logs them.
- Visualizes parsed data.

## Installation and Setup
1. Clone the repository:
2. 2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload your log file and run the cells.

## Output Files
- `structured_data.csv`: Parsed data.
- `error_log.txt`: Errors encountered during parsing.
- `visualization.png`: Data visualization.

## Assumptions
- Log files contain key-value pairs, JSON, and Base64 images.
- Invalid log formats are skipped and logged.

## Screenshots
![Visualization](visualization.png)

## Performance Analysis
- Parsing a 10 MB log file takes approximately `X` seconds.
