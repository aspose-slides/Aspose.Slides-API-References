---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/add_chart/
weight: 50
---


## add_chart {#asposeslideschartscharttype-float-float-float-float}
Creates a new chart, initializes it with sample series data and settings, and adds
            it to the end of the shape collection.

### Returns

The newly created [`IChart`](/slides/python-net/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/aspose.slides.charts/charttype) | The type of chart to add. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the chart, in points. |
| height | **float** | The height of the chart, in points. |


## add_chart {#asposeslideschartscharttype-float-float-float-float-bool}
Creates a new chart, initializes it with sample series data and settings, and adds
            it to the end of the shape collection.

### Returns

The newly created [`IChart`](/slides/python-net/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/aspose.slides.charts/charttype) | The type of chart to add. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the chart, in points. |
| height | **float** | The height of the chart, in points. |
| init_with_sample | **bool** | True to initialize the new chart with sample series data and settings; <br/><br/>            false to create the chart with no series and only minimal settings, which makes creation faster. |



### See Also
* enumeration [`ChartType`](/slides/python-net/aspose.slides.charts/charttype)
* class [`IChart`](/slides/python-net/aspose.slides.charts/ichart)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

