# #30DayMapChallenge 2021 🌎

The #30DayMapChallenge is a daily mapping/cartography/data visualization challenge that happens every November. There are no restriction on tools or data. No need to register anywhere. Just an excuse to make maps and admire maps made by others. Learn more [here](https://30daymapchallenge.com/).

## Day 1 - Points
![Day 1 - Points](/Day01_Points_ChristmasTree.png)

I saw a CBC News article that said Island Waste Management Corporation had a [list of goat farms](https://iwmc.pe.ca/christmas-trees-goat-farms/) that were accepting discarded Christmas trees as animal feed and I knew immediately that this had to be mapped.

I geocoded the goat farms and IWMC drop-off centers using the provincial civic address database, and created Voronoi polygons which indicate the closest goat farm or waste watch drop-off center for all regions of Prince Edward Island.

Created with ArcGIS Pro using Esri/John Nelson's Watercolor style.


## Day 2 - Lines
![Day 2 - Lines](/Day02_Lines_WoodlotTrail.jpg)

Rivers, roads, trails, SRTM-derived elevation contours, and wetlands (symbolized as dashed LINES). I even managed to find a transmission lines dataset in the [Government of Canada Open Data Portal](https://open.canada.ca/data/en/dataset/8ba2aa2a-7bb9-4448-b4d7-f164409fe056) to fill in that tell-tale powerline corridor through the forest.

Created with ArcGIS Pro.


## Day 3 - Polygons
![Day 3 - Polygons](/Day03_Polygons_Soils.png)

Western PEI is often referred to as "flat and wet", so what better way to verify this assertion than with soil drainage polygons and a hillshade? I was going for a minimal vintage journal article/poster look.

Created with ArcGIS Pro.


## Day 4 - Hexagons
![Day 4 - Hexagons](/Day04_Hexagons_Texture.jpg)

Several years ago I stumbled across a journal article on "road ecology" - the study of the impact of roads on wildlife and wildlife habitat that inspired this map. Despite its small size Prince Edward Island has a relatively high density of roads, leading to habitat fragmentation and potential landscape connectivity issues.

Created with ArcGIS Pro.


## Day 5 - OpenStreetMap
I have always wanted to explore using OpenStreetMap data but didn't know where to begin, so this challenge was the push that I needed. I landed on the Chernobyl Nuclear Power Plant as the subject thanks to some GPS points from a tour of the Chernobyl Exclusion Zone I found online.

OpenStreetMap data was downloaded in .PBF format from GEOFABRIK. GDAL/ogr2ogr was used to convert the .PBF data to a more GIS-friendly SpatiaLite database. I then left my comfort-zone and decided

Created with QGIS. Map data from OpenStreetMap.

## Day 6 - Red
![](/Day06_Red_Fire_Plot.png)


## Day 8 - Green
![](/Day08_Green_ForVolPro.png)


## Day 9 - Monochrome
![](/Day09_Monochrome_MtLogan.jpg)


