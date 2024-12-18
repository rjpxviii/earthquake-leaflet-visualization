# Earthquake Visualization with Leaflet

This project is an interactive map visualization of earthquake data using [Leaflet](https://leafletjs.com/). The map plots earthquakes based on their longitude and latitude and provides insights into the magnitude and depth of each earthquake. Additionally, the map includes tectonic plates boundaries to showcase the relationship between earthquake occurrences and tectonic activity.

## Data Sources

- **GeoJSON Feed**: [All Earthquakes Data in past week](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
- **Tectonic Plates Data**: [Tectonic Plates GeoJSON](https://github.com/fraxen/tectonicplates)

Click the link below to view the project preview.

## Features 
- **Earthquake Markers**:  
    - Marker size reflects the earthquake's magnitude. Larger markers signify stronger earthquakes.  
    - Marker color indicates the earthquake's depth. Darker colors represent greater depths.  

- **Popups**:  
    - Clicking on a marker reveals a popup displaying detailed information about the earthquake, including its magnitude, depth, and location.  

- **Legend**:  
    - A legend located in the bottom-right corner of the map explains the color scale used for earthquake depth.  

- **Tectonic Plates**:  
    - The map features tectonic plate boundaries, allowing users to observe the connection between earthquake locations and plate edges.  

- **Layers**:  
    - **Reference**: Base map. 
    - **Outdoors**: A detailed representation of the Earth's surface that uses contour lines to depict elevation and terrain features  

- **Layer Control**:  
    - Users can switch between various base maps and toggle the visibility of earthquake markers and tectonic plate boundaries.  

Thanks for exploring! 
