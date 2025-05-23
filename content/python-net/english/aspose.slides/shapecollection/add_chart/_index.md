﻿---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_chart/
weight: 50
---


## add_chart {#asposeslideschartscharttype-float-float-float-float}
Creates a new Chart, initialize it with sample series data and settings and adds 
            it to the end of the collection.

### Returns

Created chart.



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/aspose.slides.charts/charttype) | Type of chart. |
| x | **float** | X coordinate of a new chart. |
| y | **float** | Y coordinate of a new chart. |
| width | **float** | Chart's width. |
| height | **float** | Chart's height. |

### Examples

The following example shows how to create Chart in PowerPoint Presentation.


## add_chart {#asposeslideschartscharttype-float-float-float-float-bool}
Creates a new Chart and adds it to the end of the collection.

### Returns

Created chart.



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/aspose.slides.charts/charttype) | Type of chart. |
| x | **float** | X coordinate of a new chart. |
| y | **float** | Y coordinate of a new chart. |
| width | **float** | Chart's width. |
| height | **float** | Chart's height. |
| init_with_sample | **bool** | If true then new chart will be initialized with sample series data and settings.<br/><br/>            If false then new chart will have no series and minimum settings. In this case <br/><br/>            chart creation will be more fast. |



### See Also
* enumeration [`ChartType`](/slides/python-net/aspose.slides.charts/charttype)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

