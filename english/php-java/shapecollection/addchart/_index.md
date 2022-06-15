---
title: addChart
type: docs
weight: 70
url: /php-java/shapecollection/addchart/
---

# addChart(int, float, float, float, float) method

 Creates a new Chart, initialize it with sample series data and settings and adds 
 it to the end of the collection.
 

##  Parameters

| name | description |
| --- | --- |
| type | Type of chart. |
| x | X coordinate of a new chart. |
| y | Y coordinate of a new chart. |
| width | Chart's width. |
| height | Chart's height. |

##  Returns
Created chart.


# addChart(int, float, float, float, float, boolean) method

 Creates a new Chart and adds it to the end of the collection.
 

##  Parameters

| name | description |
| --- | --- |
| type | Type of chart. |
| x | X coordinate of a new chart. |
| y | Y coordinate of a new chart. |
| width | Chart's width. |
| height | Chart's height. |
| initWithSample | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

##  Returns
Created chart.


