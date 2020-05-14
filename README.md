# Neighborhoods_in_Toronto
Postal codes clustering of the city of Toronto, Canada, using the venues density
## Introduction

In this project is presented the segmentation and clustering of the Postal codes division of the city of Toronto in the province of Ontario, Canada, extracted from "List of postal codes of Canada: M" in Wikipedia (https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M).

The Foursquare API was used to find the venues on each postal code zone using a radius based on the area cover by each postcode without overlapping between them and a maximum number of venues per postal code of 100. Using K-Means clustering algorithm, the postal codes were grouped based on the venues density (venues/area) and the result was showed on a map of Toronto.
