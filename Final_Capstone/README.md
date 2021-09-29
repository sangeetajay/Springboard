# Predicting Home Prices from Zillow Images
![Image of Zillow Page](https://github.com/sangeetajay/Springboard/blob/master/Final_Capstone/Images/austinzillowpagesmall.png)

## Final Capstone Project for Springboard Data Science Career Track
This folder contains the notebooks, final report, and slide deck for my final capstone project for the Springboard Data Science Career Track. The dataset is from Kaggle and can be found [here](https://www.kaggle.com/ericpierce/austinhousingprices)

### Links to important files:
1. Notebooks:

    [Data Wrangling and EDA: ](https://github.com/sangeetajay/Springboard/tree/master/Final_Capstone/DataWrangling_EDA_Notebooks)
    These notebooks show the steps taken to process the images as well as the cleaning and exploratory analysis of the csv file that accompanied the images.
    
    [Pre-Processing and Modeling: ](https://github.com/sangeetajay/Springboard/tree/master/Final_Capstone/ModelingNotebooks)
    These notebooks contain the pre-processing and different models tested. Each notebook has a different type of model.    

2. Documentation:

   [Final Project Report: ](https://github.com/sangeetajay/Springboard/blob/master/Final_Capstone/SJ_final_capstone_report.pdf)
    A detailed report with descriptions of the technical work that was done on this project.

   [Final Project Presentation: ](https://github.com/sangeetajay/Springboard/blob/master/Final_Capstone/SJ_Final_Capstone_presentation.pdf)
    A slide deck with an overview of the main objectives and findings of this project.

### Objective: 
To use the dataset containing images scraped from Zillow to try to predict the home prices. 

### Modeling Strategy:
![Image of model stratgy](https://github.com/sangeetajay/Springboard/blob/master/Final_Capstone/Images/modelstrat.png)

### Model Architecture: 
Features data and image data are both fed into an MLP model and a CNN model. The outputs from the two models are concatenated to create the mixed inputs model.

![Image of model arch](https://github.com/sangeetajay/Springboard/blob/master/Final_Capstone/Images/modelarch.png)

### Conclusion:
Using the home features and image data into a mixed inputs model resulted in better model performance compared to using either method alone. 

