# Project Name
> Boom Bikes -Bike Sharing 
Boom-Bikes company reached out to a consulkting compamny to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
 -Which variables are significant in predicting the demand for shared bikes.
 -How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
  -Background: A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 : Data Understanding 
In this section, we have analysed the given dataset w.r.to it's structure. In the process, we have changed the data types of few columns and also changed some of the values based on Data Dictionary.
- Conclusion 2 : Data Visualization 
In this section, we have looked at the actual data content.We plotted few distribution plots and a correleation Matrix and heatmap for numerical varibales. We also removed one of the features "atemp" as it was highly correlated with the another varibales "temp".
- Conclusion 3 : Data Preparation
The main task done in this section are:

  -create the respective dummy variables
  -delete the irrelevant data
- Conclusion 4 : Model Building and Evaluation
In this section, we build our first model considering all the variables and then we made an informed choice based on VIF and p-values and finally made our baseline model with 7 variables. We also plotted the error term to check if they are normally distributed. Our regression line also looks pretty clustered around the central line.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- SKLearn
- Matplot and seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Machine Learning Curriculum
- References : https://learn.upgrad.com/ 



## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
