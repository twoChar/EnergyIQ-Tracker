# EnergyIQ Tracker
This repository is for a course Project in Machine Learning

# Electricity Consumption For Household Appliances
- Increasing energy consumption and environmental impact necessitate innovative solutions.
- Traditional methods of tracking household electricity lack detail, resulting in inefficient energy use and higher bills.
- Our project utilizes advanced machine-learning techniques to address these challenges.
- By leveraging submeter readings and regression models, we accurately predict and categorize electricity consumption by individual appliances.
- This empowers homeowners with precise insights to optimize energy usage, reduce costs, and contribute to sustainability.

# Our goal
- Our project employs diverse machine-learning techniques to predict household electricity usage accurately.
- Analyzing submeter readings from various appliances enables us to understand energy usage patterns and consumption behaviors.
- We aim to develop a high-performing model that identifies energy-hungry appliances and optimizes usage.
- This initiative could revolutionize energy management, promoting sustainability and cost reduction.
- The model's versatility extends to smart grid management and energy-efficient urban planning.
- Ultimately, our goal is to empower individuals and communities to make informed decisions and reduce the ecological footprint of electricity consumption.

# Dataset
- The dataset contains six months of electricity consumption records from January 2007 to June 2007 for a household.
- It includes various metrics such as global active power, global reactive power, voltage, and global intensity.
- Sub-metering data is available for specific areas within the home, including the kitchen, laundry room, electric water heater, and air conditioner.
- With a total of 260,640 measurements, this dataset is valuable for comprehending and analyzing patterns in household electricity consumption.
- Data preprocessing techniques have been applied to ensure the dataset's quality and usability for analysis.
![image](https://github.com/Shivansh20128/Electricity-Consumption-for-Household-Appliances/assets/88429611/c1b07430-9dbe-4fa2-a10e-7c569716b695)

# Methodology
Our main objective is to develop a predictive model for
predicting household electricity consumption by employing machine learning algorithms. In addressing the regression problem, we have explored different ML regression algorithms on the Dataset. 

**1. Data Preprocessing**

• Label Encoding

• Categorical Encoding

• One-Hot Encoding

• Feature Selection

• Target Variable

**2. Data Splitting**

In order to objectively assess the model’s performance,
the dataset was methodically partitioned into distinct
training and testing subsets. The training set comprised 80 percent of the data, serving as the foundation for model development, while the testing set constituted the remaining 20 percent, providing an independent dataset for rigorous model evaluation.

**3. Models**

(a) Linear Regression

(b) SGD (Stochastic Gradient Descent) Regression

(c) Ridge Regression

(d) Bayesian Regression

(e) Lasso Regression

(f) Decision Trees

(g) Random Forest Regressor

(h) MLP Regressor

(i) K Neighbours Regressor

**4. Model Evaluation**

The model’s performance was rigorously evaluated using three key metrics:

(a) Mean Squared Error (MSE)

(b) Root Mean Squared Error (RMSE)

(c) R-squared (R2) Score

**5. RESULT AND ANALYSIS**

After trying out all the regression models, we collected
results for all of them and compared them using established
metrics like MSE, RMSE, and R2 Score. Random Forest gave us
the best results.
![image](https://github.com/twoChar/EnergyIQ-Tracker/assets/88621271/bf6ac698-a212-462f-a972-9b9a83386fb2)
![image](https://github.com/twoChar/EnergyIQ-Tracker/assets/88621271/cf73e8fa-c8bc-4551-ab0e-60f9ff941003)





