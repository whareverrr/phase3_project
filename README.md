# Phase 3 Project Description

## PROACTIVE VEHICLE MAINTENANCE WITH PREDICTIVE ANALYTICS AT DRIVESURE SOLUTIONS

- ***Hawkins Murithi Kobia***


## PROJECT OVERVIEW

DriveSure Solutions aims to transform how vehicle maintenance is handled through predictive analytics. 
By analyzing comprehensive car maintenance data, the company hopes to properly estimate repair needs, improving both vehicle reliability and customer pleasure.
DriveSure Solutions intends to leverage these information to create a prediction model that would be easy to use. Once validated, this model will aid in the efficient scheduling of maintenance work, eliminating unexpected outages and giving consumers with a more seamless experience. 


## BUSINESS UNDERSTANDING

#### Stakeholders in this project include:

**- DriveSure Solutions Management:** Responsible for overall strategy and implementation.

**- Maintenance Team:** Executes maintenance tasks based on predictions.

**- Customers:** Beneficiaries of improved vehicle reliability and service experience

  
#### Business Problem

DriveSure Solutions seeks to develop a predictive maintenance model to identify vehicles that are likely to require maintenance in the near future. 
The goal is to use historical maintenance data and various vehicle attributes to predict maintenance needs accurately. 
This predictive capability will help in scheduling timely maintenance, preventing unexpected breakdowns, and ensuring smooth operation of vehicles.

#### Business Objectives

**- Enhance Vehicle Reliability:** Predict maintenance needs to minimize unexpected breakdowns and increase vehicle uptime.

**- Improve Customer Satisfaction:** Provide timely maintenance services to enhance the overall customer experience.

**- Optimize Resource Allocation:** Efficiently allocate maintenance resources to minimize downtime and operational costs.


#### Business Questions

- What factors contribute to vehicle maintenance needs?

- How can we predict maintenance needs accurately?

- What impact will proactive maintenance have on customer satisfaction?

- How can predictive analytics help optimize maintenance resource allocation?

- What tools and technologies are required to implement predictive maintenance effectively?


## DATA UNDERSTANDING

#### Vehicle_Maintenance_Data CSV Dataset

https://www.kaggle.com/datasets/chavindudulaj/vehicle-maintenance-data/data

- The dataset provided contains information on vehicle attributes, maintenance history, and reported issues.
  
- Features: Vehicle_Model, Mileage, Maintenance_History, Reported_Issues, Vehicle_Age, Fuel_Type, Transmission_Type, Engine_Size, Odometer_Reading,Last_Service_Date, Warranty_Expiry_Date, Owner_Type, Insurance_Premium, Service_History, Accident_History, Fuel_Efficiency, Tire_Condition, Brake_Condition, Battery_Status.

- Target Variable: Need_Maintenance (Binary: 1 - Maintenance needed, 0 - No maintenance needed)



## DATA ANALYSIS

- In this project, we attempted to enhance vehicle maintenance by forecasting when a vehicle will require service.

- Data collection involved gathering information about the vehicle, such as its history and reported difficulties.
  
- Data Preprocessing: We cleaned and prepared the data for analysis. This included transforming the data to a readable format and correcting any missing information.

- We balanced the dataset to ensure equal representation of vehicles in need of maintenance and those that are not. This assists in developing accurate predictions.

- We split the data into two parts: one for training the model and one for testing its performance on new data.

- Model Development: We created a model to forecast maintenance needs. We experimented with several settings until we found the optimum one for our purposes.

- Our approach achieved 97% accuracy in predicting maintenance needs.

## MODELLING

- Key Findings from Vehicle Maintenance Analysis
  
- Important Indicators:
  
Brake Condition: Vehicles with worn-out brakes are much more likely to need maintenance.
Battery Status: A weak battery is a strong signal that maintenance might be required soon.
Maintenance History: Vehicles with a poor maintenance history are more likely to need service.
Reported Issues: The more issues reported, the higher the chance the vehicle will need maintenance.

- Vehicle Models Matter:

Certain vehicle models, like cars and trucks, tend to have higher maintenance needs.

- Data Insights:
  
The top indicators for predicting maintenance needs help prioritize which vehicles to check first, potentially preventing breakdowns and ensuring safety.

- Practical Application:
  
By focusing on these key indicators, DriveSure Solutions can better predict which vehicles need service, leading to fewer unexpected breakdowns and improved customer satisfaction.

## EVALUATION

**- Logistic Regression Model**

Our Logistic Regression model achieved an accuracy of 0.81, meaning it correctly predicts maintenance needs for 81% of the instances. This model demonstrated a good balance between precision (0.83) and recall (0.78) for the class needing maintenance. This balance is crucial for identifying true positives while minimizing false positives, making it reliable for identifying vehicles requiring maintenance.

**- Random Forest Model**

The Random Forest model outperformed the Logistic Regression model with an accuracy of 1.0, indicating perfect predictive power on our test data. This model achieved a precision and recall of 1.0 for both classes, showcasing its superior ability to correctly identify true positives and minimize false negatives. The Random Forest model's robustness and high accuracy make it a powerful tool for predicting maintenance needs, ensuring proactive maintenance and vehicle reliability.



## HYPERPARAMETER TUNING

- Hyperparameter tuning significantly improved the performance of the baseline Logistic Regression model.

  
- By optimizing the model parameters, we achieved enhanced accuracy, precision, recall, F1 score, and ROC-AUC score, making the model more robust and reliable.

   
- This process underscores the importance of fine-tuning to maximize performance and ensure optimal predictive capabilities, demonstrating that careful adjustment of parameters can lead to substantial improvements in model effectiveness.



![image](https://github.com/whareverrr/phase3_project/blob/main/Tuned%20Model.PNG)) 



  ## RECOMMENDATIONS

  
  **- Brake Condition Monitoring Service:** 

Offer a specialized brake condition monitoring service that provides regular inspections and maintenance checks for customers. This service can help detect potential issues early on, ensuring optimal brake performance and enhancing vehicle safety.

**- Battery Health Assessment Program:** 

Introduce a battery health assessment program where customers can have their vehicle batteries checked regularly. By monitoring battery status and recommending timely replacements or maintenance, this program can prevent unexpected breakdowns and prolong battery life, improving overall vehicle reliability.

**- Reported Issues Resolution Initiative:** 

Implement an initiative to address reported issues promptly and effectively. Provide customers with a streamlined process for reporting vehicle problems and ensure timely resolution through expert diagnostics and repair services. This proactive approach can prevent minor issues from escalating into major maintenance problems.

   **- Customized Maintenance Plans by Vehicle Model:** 

Develop customized maintenance plans tailored to specific vehicle models. By considering the unique maintenance needs of each vehicle type, such as cars, trucks, motorcycles, and vans, these plans can optimize maintenance schedules and procedures, leading to improved vehicle performance and longevity.


  **- Proactive Recall Notification System:**

 Implement a proactive recall notification system to alert customers about potential safety issues or manufacturer recalls related to their vehicle models. By staying ahead of potential risks and facilitating timely repairs or replacements, this system can enhance customer safety and satisfaction.





