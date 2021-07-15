# Forest Cover Prediction Using pyspark
In this project, we will use the Forest Cover dataset to build **logistic regression** and **decision tree models** to predict the types of forest cover in a particular wilderness region based on cartographic information as features. We will then identify the best model with optimal hyperparameters and evaluate the best model's performance with out-of-sample (test) data.  
The data was collected from Roosevelt National Forest in Northern Colorado. Each observation represents a 30-meter by 30-meter patch of land.  
The dataset and details can be found at: https://www.kaggle.com/c/forest-cover-type-prediction/data   

**The dataset contains the following columns:**  
- **Elevation** – The average elevation of the region, in meters.  
- **Aspect** – Measures the direction the slope of the region faces, in degrees. 0 degrees indicates North.  
- **Slope** – The average slope of the region, in degrees.  
- **Horizontal_Distance_To_Hydrology** – The horizontal distance to the nearest surface water.  
- **Vertical_Distance_To_Hydrology** – The vertical distance to the nearest surface water.  
- **Horizontal_Distance_To_Roadways** – The horizontal distance to the nearest roadway.  
- **Hillshade_9am** – Measures the amount of shade the region has at 9 am during the summer solstice.  
- **Hillshade_Noon** – Measures the amount of shade the region has at noon during the summer solstice.  
- **Hillshade_3pm** – Measures the amount of shade the region has at 3 pm during the summer solstice.  
- **Horizontal_Distance_To_Fire_Points** – The horizontal distance to the nearest wildfire ignition points.  
- **Wilderness_Area** – A categorical variable indicating which of four wilderness areas the region resides in. The names of the four areas are: Rawah, Neota, Comanche Peak, and Cache la Poudre  
- **Soil_Type** – A categorical variable indicating which of 40 soil types is predominant in the region. The soil types are encoded as integers with values 1 – 40. A list of the soil types can be found on the Kaggle side linked above.  
- **Cover_Type** – A categorial variable indicating which of 7 forest cover types is predominant in the region. The cover types are encoded as integers with values 1 – 7. The names of the 7 types are provided below:  
  1. Spruce/Fir    
  2. Lodgepole Pine   
  3. Ponderosa Pine  
  4. Cottonwood/Willow  
  5. Aspen  
  6. Douglas-Fir  
  7. Krummholz 
  
**Analysis Flow:**  
  - **Part A: Set up the Environment**  
  - **Part B: Load and Explore the Data**
  - **Part C: Preprocessing and Splitting the Data**
  - **Part D: Hyperparameter Tuning for Logistic Regression**
  - **Part E: Hyperparameter Tuning for Decision Trees**  
  - **Part F: Identifying and Evaluating the Final Model**  
  - **Part G: Applying the Model to New Data:** 
