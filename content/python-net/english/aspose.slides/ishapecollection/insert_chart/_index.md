---
title: insert_chart method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/insert_chart/
weight: 240
---


## insert_chart {#asposeslideschartscharttype-float-float-float-float-int}
Creates a new Chart, initialize it with sample series data and settings and inserts 
            it to the specified position in the collection.

### Returns

Created chart.



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | **aspose.slides.charts.ChartType** | Type of chart. |
| x | **float** | X coordinate of a new chart. |
| y | **float** | Y coordinate of a new chart. |
| width | **float** | Chart's width. |
| height | **float** | Chart's height. |
| index | **int** | Chart's position in the collection. |



## insert_chart {#asposeslideschartscharttype-float-float-float-float-int-bool}
Creates a new Chart and inserts it to the specified position in the collection.

### Returns

Created chart.



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | **aspose.slides.charts.ChartType** | Type of chart. |
| x | **float** | X coordinate of a new chart. |
| y | **float** | Y coordinate of a new chart. |
| width | **float** | Chart's width. |
| height | **float** | Chart's height. |
| index | **int** | Chart's position in the collection. |
| init_with_sample | **bool** | If true then new chart will be initialized with sample series data and settings.<br/><br/>            If false then new chart will have no series and minimum settings. In this case <br/><br/>            chart creation will be more fast. |



### See Also
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
