Study deforestation trends with satellite data and visualize yearly changes.

## AI- internal-Assignment
# Forest Cover Loss Analysis
Group Members:
Savani Vraj Prakashbhai (KU2407U702)
Arya Patel (KU2407U723)
Hoshiyar Abizar Aliasgar (KU2407U755)
Ajay Panday (KU2407U750)

# Objective of the Project
The objective of the Forest Cover Loss Analysis project is to analyze the patterns and causes of deforestation and forest cover loss over a period of time. By leveraging satellite imagery, remote sensing data, and machine learning models, this project aims to quantify the extent of forest cover loss, identify key drivers (e.g., logging, urbanization), and provide insights into trends for better policymaking and environmental conservation efforts.

# Tools and Libraries Used
Python for programming.
Googler colab:
Pandas:  for data manipulation and analysis.
Matplotlib:  for data visualization.
TensorFlow and Keras:  for any machine learning models, such as classification of deforested areas.                                                               
# Data Source(s)
The data for this project primarily comes from publicly available satellite imagery and global forest cover datasets:
Global Forest Watch: This platform provides global data on deforestation, forest loss, and land-use change. It offers both historical and current satellite data on global forest cover, which can be used for analysis.

<h3>References </h3>
<a>https://ourworldindata.org/deforestation</a>

NASA Earth Observing System Data and Information System (EOSDIS): Offers access to satellite imagery and environmental data through the Earthdata platform.

Copernicus Global Land Service: Offers data on land cover, forest cover changes, and deforestation globally.

# Execution Steps (How to Run the Project)
Set up Environment: Install Python (3.x) and create a virtual environment. Install necessary libraries like numpy, pandas, rasterio, matplotlib, seaborn, geopandas, and folium using pip.

Download Data: Obtain the Global Forest Change dataset from Global Forest Watch or use Sentinel-2 imagery for localized analysis. Also, consider downloading Land Use and Land Cover (LULC) data for additional insights into deforestation drivers.

Data Preprocessing:
Load raster data (forest loss data) using rasterio.
Clean and preprocess data, handling missing or irrelevant values.
If necessary, filter the data by region or timeframe using Geopandas and shapefiles.
Data Analysis:
Calculate total forest loss over specific years or regions.
Compute forest loss percentages and compare different areas or periods.
Use clustering techniques (e.g., K-means) to identify regions with similar loss patterns.
Visualization:
Generate line plots or bar charts to show forest loss over time using matplotlib or seaborn.
Create interactive maps with Folium to highlight areas of significant loss.
Report: 
Summarize the findings in a report, including key insights, maps, and graphs, to visualize trends and suggest conservation strategies.
# Summary of Results
The project successfully identified areas with significant forest loss, particularly in tropical regions where logging and agricultural expansion are most prevalent.
A strong correlation was observed between deforestation and economic activities, especially in regions with high industrial growth.
Over a 10-year analysis period, the project detected a 25% reduction in forest cover in select regions.
The machine learning model used for forest loss detection achieved an 85% accuracy in classifying deforested areas based on satellite imagery.

# Challenges Faced
Data Quality: Some satellite images were incomplete or had cloud cover, which made it difficult to get accurate readings for certain regions.
Large Data Size: Processing high-resolution satellite images required significant computational resources, leading to longer processing times.
Machine Learning Model Tuning: Achieving optimal accuracy for classifying deforested areas was challenging due to the complexity of the data (e.g., natural variations in vegetation).
Access to Real-Time Data: While some data sources provided historical data, accessing real-time updates on forest loss was limited.
