# MSDS696earthquake
Tsunami Prediction: This project focuses of model that predicts tsunami after earthquake. By model learning, I will initally go with KNN Classifier so predict and understand the pattern.

Project Overview: this is a descriptive analysis of available data on earthquakes and its pattern, how it triggers tsunami is coastal region. this involves manipulation of data, model application, finding optimal model and further manipulation of data to enhance the result.

Data Description: Initally there was 18 columns, dropped it down to 12.The dataset newdf includes the following columns:
title: title name given to the earthquake
magnitude: The magnitude of the earthquake
date_time: date and time
cdi: The maximum reported intensity for the event range
alert: The alert level - “green”, “yellow”, “orange”, and “red”
tsunami: "1" for events in oceanic regions and "0" otherwise
sig: A number describing how significant the event is. Larger numbers indicate a more significant event. This value is determined on a number of factors, including: magnitude, maximum MMI, felt reports, and estimated impact
nst: The total number of seismic stations used to determine earthquake location.
magType: The method or algorithm used to calculate the preferred magnitude for the event
depth: The depth where the earthquake begins to rupture
latitude / longitude: coordinate system by means of which the position or location of any place on Earth's surface can be determined and described
location: location within the country(description from earthquake dataset by Chirag Chauhan)

EDA: the EDA shows the alerts level and magnitude, number of earthquakes, geo loaction plot of earthquakes that occoured.
Model and result: the inital choice(Knn Classifier) gave the prediction accuracy of 78%. looking into other model, Decision Tree Classifier had a better outcome of 91%.
    Tried random forest classifier and result came to 93%. dropped less important column and tried RF anf result came to 100%

