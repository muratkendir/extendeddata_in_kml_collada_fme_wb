## Adding ExtendedData into Collada + KML dataset using 3DCityDB

By uploading Collada + KML datasets into Cesium Ion or any Cesium data server, it is possible to visualize some essentail attributes. On the other hand, it is also possible to add other attributes to the model by using <ExtendedData> tag in KML Placemark object.
This FME Workbench file is a working sample, which is querying generic attributes and addresses of buildings by connecting to 3DCityDB, which was source of Collada+KML dataset and exported by Importer/Exporter Tool.

For more information, please visit following links:

Create 3D Tiles from KML/COLLADA with Per-Building Data
https://cesium.com/blog/2020/04/09/kml-collada-metadata/

3DCityDB and Importer/Exporter Tool:
https://www.3dcitydb.org/3dcitydb/

Shoot a glance to FME Workbench as PDF file:
[/docs/fme_whole_workbench.pdf](/docs/fme_whole_workbench.pdf)

![ExtendedData Attributes in Cesium](/docs/screenshot_in_cesium.png)


