# Total_Sales_Predictor

This project explores solution to Techgig machine learning challenge. The problem is to predict the total sales a new outlet of a company may produce if opened at some particular location based on the given historical data of running outlets. 

## Getting Started

The [Training_Normal_Dataset.ipynb](https://github.com/mohitgoel188/Total_Sales_Predictor/blob/master/Training_Normal_Dataset.ipynb) file is the main file which contains all training related code code done on actual data provided .  
The [Training_Improved_dataset.ipynb](https://github.com/mohitgoel188/Total_Sales_Predictor/blob/master/Training_Improved_Dataset.ipynb) uses improved dataset in which location coordinates are used to get various important features like popuation count. The data transformation is done in [Data Cleaning.ipynb](https://github.com/mohitgoel188/Total_Sales_Predictor/blob/master/Data%20Cleaning.ipynb)  
  

*.ipynb* is a python3 jupyter notebook and can be opened like any other jupyter notebook.

## Table Schemas
* *test.csv/train.csv*    
    [outlet_no | business_type | city | state | zip | store_location | avg_age | blue_collar | white_collar | female | male | total_household_size  | total_household_income | time_zone | latitude | longitude | location_employee_code | employee_size | credit_score | credit_score_range | actual _credit_score]

* *testX.csv/trainX.csv*    
    [outlet_no | business_type | zip | avg_age | blue_collar | white_collar | female | total_household_size  | total_household_income | latitude | longitude | employee_size | actual _credit_score | Median | Pop | Encoded_store_location | Encoded_city | Encoded_state | Encoded_time_zone | Encoded_location_employee_code]


### Prerequisites

Python 3.6.x is required with following modules with their dependencies:-
* sklearn    
    -- For constructing model,training,predicting
* jupyter notebook                            
    -- For interactive feedback
* numpy                                       
    -- For numerical computation on arrays
* pandas  
    -- For loading data from .csv file and doing manipulation on it if required
* beakerx (optional)    
    -- For getting more interactive table view
* matplotlib (optional)                       
    -- For text image visualization

### Installing

Python 3 can be found at [this link](https://www.python.org/downloads/)
All further modules can be installed by passing: `pip install module_name` in the command shell(cmd, Windows Powershell,etc.) 