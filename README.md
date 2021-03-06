# geomappingcensus
3D Plots of Census Data onto GeoJSON shape files

These R scripts plot census data on a ward level. Plots include 
* choropleth maps showing population per ward (heatmap)
* choropleth maps highlighting wards with substantial levels of poverty
* 3D elevation map plots showing population per ward (elevation by population, heatmap by population)
* 3D elevation map plots highlighting wards with substantial levels of poverty (elevation still by population, red highlighting of particularly poor wards)

See 3d elevation examples here: 
Gauteng Population Density http://bit.ly/1J8Zhnd 
Western Cape (Urban Subset) density and poverty http://bit.ly/1Iyt3Bh

See choropleth map examples here:
Gauteng Population Density http://bit.ly/1IvJ4JO
Gauteng Substantial Poverty Wards http://bit.ly/1HbtO1E

For the purposes of this demonstration, wards with "Substantial Poverty" were defined as having more than 50% of households subsisting on less than R38,200 per annum. 

The data for this example came from the 2011 Census: http://www.statssa.gov.za/

The ward / municipality / province outlines came in .shp format from http://www.demarcation.org.za/ but are much more easily accessed from https://github.com/Code4SA/SA-Maps

Created for a Code4SA Hackathon :-)
