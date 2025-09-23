# Drug Poisoning Mortality Data Analysis (1999-2018)
## Project Overview
This project analyzes drug poisoning mortality data in the United States from 1999 to 2018. The analysis focuses on identifying trends in drug poisoning deaths by age group, over time, and across different states. The project utilizes Python libraries such as pandas for data manipulation, matplotlib and seaborn for static visualizations, and plotly for interactive visualizations, including a choropleth heatmap. A Gradio application is developed to provide an interactive interface for exploring the data and visualizations.

## Data Source
The data used in this project is sourced from the National Center for Health Statistics (NCHS) - Drug Poisoning Mortality by State, United States (1999-2018).

## Analysis and Visualizations
Total Deaths By Age Group
A bar chart is generated to show the total number of drug poisoning deaths by age group, excluding the "All Ages" category. This visualization highlights the age groups with the highest number of deaths.

## Total Drug Poisonings Per Year
A line graph illustrates the trend of total drug poisoning deaths in the United States from 1999 to 2018, showing the overall increase in mortality over this period.

## Total Deaths in the Top 10 States
A pie chart displays the proportion of total drug poisoning deaths accounted for by the top 10 states with the highest average crude death rates, indicating the concentration of deaths in certain states.

## Heatmap of Crude Death Rate by State Over Time
An interactive choropleth heatmap visualizes the crude death rate by state over time, allowing for the exploration of geographical and temporal trends in drug poisoning mortality across the US.

## Death Rate Trend Over Time per State
An interactive line plot allows users to select a specific state and view its crude death rate trend over time.

## Gradio Application
A Gradio application is built to serve as an interactive dashboard for presenting the visualizations and allowing users to explore the data. The application includes tabs for each visualization and a dropdown for selecting states in the death rate trend plot.

## Files
-NCHS_-_Drug_Poisoning_Mortality_by_State__United_States.csv: The primary dataset used for the analysis.
-This markdown file (README.md or similar): Provides an overview of the project.
-Jupyter Notebook (e.g., drug_poisoning_analysis.ipynb): Contains the code for data loading, analysis, visualization, and the Gradio app.

## How to Run the Project
-Ensure you have the necessary libraries installed (pandas, matplotlib, seaborn, plotly, geopandas, gradio, requests).
-Download the dataset and place it in the specified file path or update the code with the correct path.
-Run the Jupyter Notebook cells sequentially.
-Launch the Gradio application from the notebook to interact with the visualizations.