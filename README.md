# KML Mapping Of An Area
The main goal of this project was to improve the KML files that represent the university.
The mapping went through multiple processes:
- The first one was to gather the KML files and separate the polygon, space, line, and point
KML files.
- For the second step, we created multiple new points that were originally missing from the
provided KML files for the L section.
- The third step consisted of adding new non-spatial attributes to the KML files. This could
be done in several different ways - using QGIS, text editor, XML files. We used text
editor approach, quicker and efficient way, to add all non-spatial attributes like ID, Type,
From, To, Description, etc.
- The last step was to convert all KML files to shape files, using in-built function - ‘Add
layer’ of QGIS Software. Converted polygons/space KML files to polygons/space shape
files, and similarly line shape files and the point shape files. Having all four merged
shape files for each polygon, spaces, line, and points we then merged these four shape
files into one presenting the entire shape file for the L section.
- The finishing process was converting the merged shapefiles for each polygon, space, line,
point, and the merged L section back to one KML file.
