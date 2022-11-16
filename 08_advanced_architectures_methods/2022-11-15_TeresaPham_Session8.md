### How could you use AI for a problem that interests you?
I could use AI to examine trends I see in a dataset to effectively analyze any correlations I see between elements of the data. For example, with the Covid-19 cases, I can use AI to estimate the mortality rate and/or hospital cases by year. Also, I can use AI to generate a model that can identify which regions have the most cases using the gaussian model.


### What is the task?
The main task would be to identify which regions are more likely to have higher Covid-19 mortality rates (deaths/population) and if these rates will continue to rise or not.


### What kind of data would you use?
I would use data from covid.cdc.gov or another government source to affirm the accuracy of the data, and because this data is most up to date by month/year.


### What kind of method or model might be appropriate?
A gaussian mixture model may be accurate because the elliptical shape will change and encompass the general area with relatively higher accuracy than a k-means model.


### What kind of metric would you use to measure success?
I would use cross validation by dividing the data into 5 parts: 80% for training data and 10% for test data. From here, I can generate the centroids/centers to form clusters that will evolve with each iteration of these folds.