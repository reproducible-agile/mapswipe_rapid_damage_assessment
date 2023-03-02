# See detailed description an tutorial in jupyter/Demonstration.ipynb
This provides a demonstration for the paper "Exploring MapSwipe as a Crowdsourcing Tool for (Rapid) Damage Assessment: The Case of the 2021 Haiti Earthquake". To ensure reproducibility the findings of the paper are demonstrated here.

# Maps
Maps were created in QGIS. QGIS files and resp. data can be found in the "Maps" folder. It contains the qgis project file with the map layouts, as well as the geopackage file conaining the data.
By opening the .qgz file in QGIS it is possible to access the maps for the paper via the print layouts.

# Installation
For installation create a new anaconda environment with the provided .yml file.
Direct into the directory of this readme file and run the following command:
```
    conda env create -f rapid_damage_assessment_installation.yml
```