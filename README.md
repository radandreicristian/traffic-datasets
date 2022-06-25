# Traffic Forecasting Datasets

This repository contains a collection of the most frequently used datasets for traffic forecasting. 

Multiple authors and open-source projects provide access to these datasets. One issue is the lack of consistency and the deprecated ways in which these datasets were stored initially. 

To address this issue, this repository aims to provide consistent, modern, ready-to-go access to the most used datasets in the traffic forecasting literature.

## Folder Structure

Each folder, corresponding to a dataset contains (at least) the following:

* *readings.csv* - The values of the sensor readings - Each column represents a sensor and each line represents represents a time interval. 
* *sensors.txt* - A list of the IDs of the sensors of interest.
* *distances.csv* - A file containing the dinstances (physical) between pairs of sensors. Each line is of shape "from, to, distance" for sparsification.

## Requirements

NumPy ~ 1.20
Pandas ~ 1.3.4

## Contributing

To contribute, please open a pull request with data corresponding to anothre traffic forecasting dataset, respecting the provided format. 

## License

This repository is under the MIT License. You can do whatever you want with it and you won't be sued for any rights.
