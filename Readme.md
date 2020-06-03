# US-BORDER-CROSSING

This dataset contains all the incidents of crossing the border into the US as provided by the Bureau of Transportation Statistics, Govt. of the US. This dataset tells about the incoming counts into the US.

This can prove to be a vital dataset to predict the average incoming counts into the future seeing the current trend. A primary look tells us that 77% of the incidents marked in the dataset consisted of US-Canada border meaning Canadians have tended to come in more frequently into the US as compared to the Mexicans.

This data can also prove to useful to predict the daily or weekly or monthly or annual traffic that's going to accumulate on the borders so that the authorities can be aware of the number beforehand.

We will perform exploratory data analysis with python to get insight from the data.

# Tools and Libraries Used
We have used the following python packages to perform the visualization

* Pandas
* Matplotlib
* Seaborn
* Numpy

# Motivation

In this notebook we are going to try explore the data we have and going try answer questions like:
* How's the trend of border crossings looks?
* Month wise trend of border cossing
* Is there unexpected sharp spikes or drops and why?
* Which port is mostly used for border crossing?
* Which border and state is busier than other/s?
* What are the most common entry vehicles used by the passengers?


# Files

The repository contains two files other than the readme file
US_BORDER_DATA.ipynb: Jupyter Notebook file contains all the python code, documentation and visualization
Border_Crossing_Entry_Data.csv: Our dataset file

Dataset contains the following features:
* Port Name
* State
* Port Code
* Border
* Date
* Measure
* Value

# Result

We learned that:

* The border crossing increase for the first four years if the data and then declined over the years, could be inferred the policies could have been made strict.
* US-Mexico border is a more busy border in United States
* Personal Vehicles are mostly used by people to cross the border followed by Pedestrains and Trucks
* El-Paso and San Ysidro are the most busiest ports where crossing done
* Texas state is what mostly people use for crossing border, which is US-Mexico border
* Month wise the border crossing remains the same over the year with a spike in July and August months.

# Dataset Information

The dataset was posted on kaggle. It is avaiable to download here [US BORDER Crossing Dataset](https://www.kaggle.com/divyansh22/us-border-crossing-data)
