# matplotlib-challenge

## Module 5 Challenge  

## Instructions

This repository contains the matplotlib-challenge for Module 5. To see this code in action clone the repository. It includes an analysis of the effectiveness of various drug regimens on tumor growth in mice, using data visualization techniques with matplotlib. The code provided generates a series of graphs that help in understanding the impact of different drug treatments on tumor size and mouse survival rates. You can see the difference in the starting point of this assignment by looking at the [pymaceuticals_completed.ipynb](https://github.com/myhre062/matplotlib-challenge/blob/main/Pymaceuticals/pymaceuticals_completed.ipynb) file. You can see the work I contributed in the [pymaceuticals_starter.ipynd](https://github.com/myhre062/matplotlib-challenge/blob/main/Pymaceuticals/pymaceuticals_starter.ipynb) file. To interact with the code navigate to the spot where you cloned the project in your terminal. Once you are in the `pandas-challenge` folder run the command `jupyter notebook`. (The most recent version of jupyter notebook should be installed on your machine for the best performance.)

### Dependencies

To run the analysis, ensure you have the following Python libraries installed:

- matplotlib

- pandas

- scipy

### Data Files

The data required for this analysis is located in two CSV files:

- Mouse_metadata.csv

- Study_results.csv

These files should be placed in a directory named 'data' at the root of this project.

### Summary

The analysis is structured into various sections, each focusing on different aspects of the data:

1.  **Bar and Pie Charts**: Display the effectiveness of drug regimens in terms of survival rates and the distribution of male vs. female mice.

2.  **Quartiles, Outliers, and Boxplots**: Focus on tumor volume reduction across different drug regimens and identify any outliers in the data.

3.  **Line and Scatter Plots**: Examine the effect of the Capomulin treatment on individual mice and the relationship between tumor volume and mouse weight.

4.  **Correlation and Regression**: Analyze the correlation between mouse weight and tumor volume and fit a linear regression model.  

#### Key Findings:

- Drugs like Capomulin and Ramicane are more effective in reducing tumor size.

- There's a strong correlation between tumor size and mouse weight, especially in the Capomulin regimen.

- Some outliers exist which may require further investigation.

### Limitations and Considerations

While the analysis provides valuable insights, there are some limitations to consider:

- The sample size for each drug regimen varies, which might affect the generalizability of the results.

- The study has a slight male bias in the mice population.

- Outliers, while highlighted, require further investigation to understand their causes.

For a more comprehensive understanding of the data, it is recommended to perform additional statistical tests and consider a broader range of drug regimens and biological variables.