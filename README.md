# Netflix Data Analysis

A comprehensive data science project analyzing Netflix's content library to uncover patterns, trends, and insights into the streaming platform's content strategy and evolution over time.

## Project Overview

This project demonstrates a complete data science workflow using real-world Netflix data. The analysis focuses on understanding how Netflix's content strategy has evolved, identifying key trends in content production, genre popularity, and geographical distribution across the platform.

## Objectives

- Analyze historical content trends on Netflix
- Identify patterns in Movies vs TV Shows distribution
- Discover the most popular genres and their evolution
- Understand country-wise contributions to Netflix's library
- Visualize key insights for stakeholder communication

## Methodology

### 1. Data Cleaning

- Loaded and processed the `mymoviedb.csv` dataset
- Identified and handled missing values appropriately
- Standardized date formats for temporal analysis
- Cleaned and organized categorical variables (genres, countries, ratings)
- Validated data integrity and quality

### 2. Exploratory Data Analysis (EDA)

- Compared the distribution of Movies versus TV Shows
- Analyzed genre frequency and popularity trends
- Examined content production across years
- Investigated country-wise contribution patterns
- Identified key statistics and summary metrics
- Explored correlations and relationships in the data

### 3. Data Visualization

Created clear and informative visualizations using:

- **Matplotlib** - for foundational plotting and customization
- **Seaborn** - for statistical and aesthetic visualizations

Key visualizations include:
- Genre popularity bar charts and distributions
- Yearly release trends and time series analysis
- Content type distribution pie charts and comparisons
- Country-wise contribution analysis
- Heatmaps and correlation matrices

## Repository Structure

```
Netflix-data-analysis/
├── README.md                              # Project documentation
├── movie_Data_Analysis.ipynb              # Main analysis notebook
├── data/
│   └── mymoviedb.csv                      # Source dataset
└── images/                                # Generated visualizations
```

## Dataset Information

- **Source File**: `mymoviedb.csv`
- **Format**: CSV (comma-separated values)
- **Contents**: Netflix content library metadata including titles, release dates, genres, countries, and content types

## Technologies and Libraries

### Core Libraries

- **Python 3.x** - Programming language
- **NumPy** - Numerical computing and array operations
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Plotting and visualization
- **Seaborn** - Statistical data visualization

### Environment

- **Jupyter Notebook** - Interactive analysis and documentation environment

## Installation and Setup

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/shivani-vishwakarmaa/Netflix-data-analysis.git
cd Netflix-data-analysis
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required dependencies:
```bash
pip install numpy pandas matplotlib seaborn
```

### Running the Analysis

Execute the Jupyter Notebook:
```bash
jupyter notebook Notebook/movie_Data_Analysis.ipynb
```

Then navigate to the notebook and run the cells sequentially to reproduce the analysis.

## Key Findings

The analysis provides insights into:

- The ratio of movies to TV shows on Netflix
- Top genres and their market share
- Trends in content production over years
- Geographic distribution of content creators
- Evolution of Netflix's content strategy

## Usage

1. Ensure all dependencies are installed
2. Run the Jupyter Notebook from the `Notebook/` directory
3. Execute cells in order to see data processing, analysis, and visualizations
4. Generated visualizations are saved in the `images/` folder
5. Modify analysis parameters as needed for further exploration

## Future Enhancements

Potential areas for expansion:

- Machine learning models for content recommendation prediction
- Sentiment analysis of titles and descriptions
- Budget and revenue analysis (if data becomes available)
- Interactive dashboards using tools like Plotly or Dash
- Comparative analysis with other streaming platforms
- Time series forecasting for future content trends

## Results and Insights

All visualizations and key findings are documented in the Jupyter Notebook and exported to the `images/` directory for easy reference and presentation.

## Author

Shivani Vishwakarmaa

## License

This project is open source and available under the MIT License.

## Contact

For questions or discussions about this project, please open an issue on GitHub or contact the repository owner.

---

**Last Updated**: May 2026
