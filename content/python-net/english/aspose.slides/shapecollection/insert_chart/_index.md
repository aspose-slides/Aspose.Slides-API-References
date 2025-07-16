---
title: insert_chart method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_chart/
weight: 240
---


## insert_chart {#asposeslideschartscharttype-float-float-float-float-int}
Creates a new chart, initializes it with sample series data and settings,
            and inserts it into the shape collection at the specified index.

### Returns

The newly created [`IChart`](/slides/python-net/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/aspose.slides.charts/charttype) | The type of chart to create. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the new chart, in points. |
| height | **float** | The height of the new chart, in points. |
| index | **int** | The zero-based index at which to insert the new chart in the shape collection. |


## insert_chart {#asposeslideschartscharttype-float-float-float-float-int-bool}
Creates a new chart, initializes it with sample series data and settings,
            and inserts it into the shape collection at the specified index.

### Returns

The newly created [`IChart`](/slides/python-net/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/aspose.slides.charts/charttype) | The type of chart to create. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the new chart, in points. |
| height | **float** | The height of the new chart, in points. |
| index | **int** | The zero-based index at which to insert the new chart in the shape collection. |
| init_with_sample | **bool** | True to initialize the new chart with sample series data and settings; <br/><br/>            false to create the chart with no series and only minimal settings, which makes creation faster. |



### See Also
* enumeration [`ChartType`](/slides/python-net/aspose.slides.charts/charttype)
* class [`IChart`](/slides/python-net/aspose.slides.charts/ichart)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

