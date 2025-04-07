# Startup Ecosystem Analysis

This project provides a comprehensive analysis of a startup ecosystem using data from a CSV file. It leverages Python libraries like pandas, NumPy, Matplotlib, and Seaborn to extract insights and visualize key trends.

## Features

- **Basic Ecosystem Metrics:** Calculates total funding, unique companies, average round size, and total deals.
- **Time-based Analysis:** Plots year-over-year funding growth.
- **Funding Trends Analysis:** Analyzes and visualizes monthly funding patterns and average deal size by funding round.
- **Industry Analysis:** Shows funding distribution by industry and identifies top industries.
- **Geographic Analysis:** Visualizes top locations by total funding.
- **Investor Analysis:** Identifies the most active investors and their deal counts.
- **Custom Insight:** Provides a heatmap to analyze average deal size by industry and location.

## Usage

1.  **Data:** Ensure you have a CSV file containing startup funding data with relevant columns (e.g., company name, date, amount raised, industry, location, funding round, lead investor).
2.  **Code:** Place the provided Python code in a Colab notebook or a Python script.
3.  **Execution:** Run the code to perform the analysis and generate visualizations.
4.  **Customization:** Modify the file path to your data file and adjust the analysis parameters as needed.

## Dependencies

-   pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   datetime

## Getting Started

1.  Install the required libraries: bash pip install pandas numpy matplotlib seaborn
2.  Create an instance of the `StartupEcosystemAnalysis` class with the path to your data file.
3.  Call the `run_all_analysis` method to execute all analysis functions.

## Example

python analysis = StartupEcosystemAnalysis("startup_funding_data.csv") 
analysis.run_all_analysis()

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.
