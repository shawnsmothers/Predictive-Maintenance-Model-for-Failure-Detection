# Predictive-Maintenance-Model-for-Failure-Detection
EDA and Logistic/ Random Forest Classification model on Equipment Failure 


### Overview
This project focuses on building and evaluating a logistic regression model to predict equipment failures using operational data. The model is trained on a dataset containing various features such as rotational speed, torque, and tool wear, and demonstrates exceptional accuracy in identifying potential failures. The insights gained from this model can be used to enhance safety, reduce downtime, and optimize maintenance schedules in industrial settings.

### Dataset
The dataset contains the following features:

UDI: Unique identifier for each entry.
Type: The type/category of the product.
Air temperature [K]: The temperature of the air surrounding the equipment, measured in Kelvin.
Process temperature [K]: The process temperature where the equipment operates, measured in Kelvin.
Rotational speed [rpm]: The speed at which a component is rotating, measured in revolutions per minute.
Torque [Nm]: The torque applied, measured in Newton-meters.
Tool wear [min]: The amount of time (in minutes) a tool has been in use.
Target: The binary outcome variable indicating whether a failure occurred (1) or not (0).
Failure Type: The specific type of failure, if applicable.
Model Performance
The logistic regression model achieved the following performance metrics:

Accuracy: 99.9%
Precision: 1.00 (for both classes)
Recall: 1.00 (for non-failures) and 0.97 (for failures)
F1-Score: 1.00 (for non-failures) and 0.98 (for failures)
Cross-Validation Mean Accuracy: 99.9%
These results indicate that the model is highly effective at predicting failures, with only two misclassifications out of 2000 test instances.

### Insights
Higher values of Tool wear [min], Rotational speed [rpm], and Torque [Nm] were found to correlate strongly with the likelihood of failure. This suggests that as tools wear out, and both applied torque and rotational speed increase, the risk of failure becomes more significant.
Safety Implications: By monitoring these key features in real-time, organizations can implement predictive maintenance strategies that preemptively address conditions leading to failures. This not only enhances operational safety but also reduces downtime and associated costs.
