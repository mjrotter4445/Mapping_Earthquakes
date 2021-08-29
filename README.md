# Mapping_Earthquakes
*An interactive earthquake map with JavaScript and Leaflet*
 
<p align="center">
   <img width="1000" height="100" src="https://github.com/mjrotter4445/Mapping_Earthquakes/blob/main/Earthquake_Challenges/Resources_Images/coolgraphicmeter.jpg">
</p>  

***Note:*** Final documents are stored in Earthquake_Mapping folder/directory seen above. Please find the explanation of the files below. Code needs an API Key from Mapbox in order to run. The API key is not included here but safely secured in config files.   Other files (i.e. Earthquakes_past7days, Simple_Map and json files) are included because of the detailed procedure and work with with Mapbox, Leaflet and GitHub branching practice.  

## Project Overview
## Purpose

For this project I am creating an **interactive map** that shows the latest **earthquake activity around the world**. Maps allow us to explore, understand and make decisions about our world. Providing data-driven storytelling on disasters around the world and building insightful data visualization with interactive features is a valuable addition to the knowledge and awareness of planet Earth. 

**The map of earthquakes around the world contains:**

-	Toggle on/off button for **fault lines** of tectonic plates.
-	Toggle on/off button for **earthquakes of the past 7 days**.
-	Toggle on/off button for **major earthquakes of magnitude above 4.5**.
-	Three different **map styles**:
    - Street view.
    - Satellite view. 
    - Dark view.
-	**A popup marker** with information about the location and magnitude of the earthquake.
-	**The diameter** and **the color** of a marker reflect the strength of the earthquake (darker color with larger diameter represent earthquakes with a higher magnitude).
-	**A color coded legend** with the information/context for the map colors in lower right corner.

**The Toggle Menu/Legend** in the upper right corner looks like this:  
<p align="center">
<img src="https://github.com/mjrotter4445/Mapping_Earthquakes/blob/main/Earthquake_Challenges/Resources_Images/IMG_4009.JPG" width="30%" height="20%">
</p>
<p align="center">
The menu with on/off toggle buttons
</p>

**When selected,** these are the results and choices displayed:  

<p align="center">
<img src="https://github.com/mjrotter4445/Mapping_Earthquakes/blob/main/Earthquake_Challenges/Resources_Images/streets.jpg" width="60%" height="60%">
</p>
<p align="center">
An interactive world map of earthquakes - Streets View Style
</p>

<p align="center">
<img src="https://github.com/mjrotter4445/Mapping_Earthquakes/blob/main/Earthquake_Challenges/Resources_Images/Satellite.png" width="60%" height="60%">
</p>
<p align="center">
An interactive world map of earthquakes - Satellite View Style
</p>

<p align="center">
<img src="https://github.com/mjrotter4445/Mapping_Earthquakes/blob/main/Earthquake_Challenges/Resources_Images/Dark.png" width="60%" height="60%">
</p>
<p align="center">
An interactive world map of earthquakes - Dark View Style
</p>

<p align="center">
<img src="https://github.com/mjrotter4445/Mapping_Earthquakes/blob/main/Earthquake_Challenges/Resources_Images/popups%20with%20info.png" width="40%" height="40%">
</p>
<p align="center">
An interactive world map of earthquakes Pop up information displayed
</p>

## Background

Creating interactive maps is supported by specifically developed tools. For this project I used the following:

-	**Mapbox API**, an open source mapping platform for custom designed maps. 

-	**Leaflet**, a JavaScript library, designed to build the web mapping applications. 

-	**GeoJson** files that are specifically design to host geographical information. GeoJson files are the industry standard for representing simple geographical features, such as points, linestrings and polygons and non-spatial attributes, such as magnitude of the earthquake, hurricane strength, hail size, elevation, etc.

## Resources
**Data Source:**
- GeoJson file for Tectonic Plates retrieved from GitHub repository: https://github.com/fraxen/tectonicplates/tree/master/GeoJSON
- GeoJson file for Earthquakes for the past 7 days retrieved via API call from USGS website: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
- GeoJson file for Major Earthquakes (M4.5+) for the past 7 days via API call from USGS website: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

**Software:**
-	Mapbox API static/js/challenge_logic.js
-	VS Code and Chrome Developer Tools

**Languages:**
-	JavaScript, 
-	index.html (HTML) and static/css/style.css (CSS)

**Libraries:**
- D3, Leaflet

