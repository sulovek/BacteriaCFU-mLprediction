## Bacterial CFU/mL Prediction from Optical Density Data

This project uses linear regression to predict the colony forming units per milliliter (CFU/mL) of bacteria from the optical density (OD) measurements. The OD is a measure of how much light is absorbed by a liquid sample, and it is proportional to the concentration of bacteria in the sample. The CFU/mL is a measure of how many viable bacteria are present in the sample, and it is determined by counting the number of colonies that grow on a solid medium after dilution and incubation.

The data here are randomly generated for demonstration purpose only. 

The project consists of the following files:

* regression_sample_data.csv: The raw data file that contains the OD and CFU/mL values for 100 samples.
* linearregression.ipynb: The Jupyter notebook that performs the data exploration, visualization, and linear regression using Python libraries such as pandas, seaborn, and scipy.stats.

## How to use

To use this project, you need to have Python 3 and the required libraries installed on your system. You can clone this repository or download the files to your local machine. Then, you can run the following commands in your terminal:

To explore and visualize the data, run linearegression.ipynb

To analyze your own experiment data, copy and paste the data in the example dataset (regression_sample_data.csv). 

To predict the CFU/mL for a given OD value, change the value in the line <b> prediction = model.predict([[0.2]]) </b> In the example, prediction of CFU/mL for OD 0.2 is done and the predicted CFU/mL is printed in the next line. 


## Limitations
This project has some limitations that should be considered before using it for practical purposes:

The data used for this project is synthetic and may not reflect the real-world relationship between OD and CFU/mL.
The linear regression model assumes a linear relationship between OD and CFU/mL, which may not hold true for all types of bacteria or samples.
The linear regression model does not account for any measurement errors or uncertainties in the OD or CFU/mL values.
The linear regression model may not generalize well to new or unseen data that is outside the range of the training data.

## Suggestion and Collaboration
sulovekoirala@gmail.com