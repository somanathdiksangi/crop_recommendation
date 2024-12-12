Crop Recommendation  

A simple machine learning project to recommend the best crop based on soil, weather, and other data.  

What's Inside  
- A trained ML model for crop prediction.  
- A dataset folder with the data used for training and testing.  
- Easy-to-follow scripts for training and using the model.  

Dataset Details
The dataset folder includes structured data with the following features:

- N (Nitrogen content in the soil)
- P (Phosphorus content in the soil)
- K (Potassium content in the soil)
- Temperature (Average temperature)
- Humidity (Average humidity level)
- pH (Soil pH level)
- Rainfall (Amount of rainfall)
- Label (Crop type recommendation based on the conditions)
 

How to Use  
1. Clone this repository:  
   
   git clone https://github.com/somanathdiksangi/crop_recommendation.git
   cd crop_recommendation
  
2. Load the dataset in your Python environment:  

   import pandas as pd
   data = pd.read_csv('dataset/Crop_recommendation (2).csv')
   print(data.head())
   
3. Train the model or use the pre-trained version to predict crops.  

Why This Project?

This project focuses on helping farmers select the best crops based on soil, weather, and environmental conditions using a machine learning model. 
Farmers often face challenges in choosing the right crop due to varying soil health, unpredictable weather, and limited access to expert advice. 
This system provides data-driven recommendations, which can:  

- Increase crop yields by suggesting the most suitable crops.  
- Optimize resource usage like water, fertilizers, and time.  
- Reduce financial risks associated with incorrect crop selection.  
- Promote sustainable farming practices by aligning recommendations with environmental conditions.  

By offering a simple and accessible solution, this project aims to empower farmers, enhance agricultural productivity, and contribute to better farming outcomes.  



