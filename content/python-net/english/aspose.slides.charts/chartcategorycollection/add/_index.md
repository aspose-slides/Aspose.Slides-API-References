---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartcategorycollection/add/
weight: 10
---


## add {#asposeslideschartsichartdatacell}
If category exists in collection, return it. Else creates new chart category from 
[`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell) and adds it to the collection.

### Returns

Added or existing category.



```python
def add(self, chart_data_cell):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell) | Cell used to create chart category. |


## add {#any}
Creates new [`ChartCategory`](/slides/python-net/aspose.slides.charts/chartcategory) from value and adds it to the collection.

### Returns

Added [`IChartCategory`](/slides/python-net/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| value | **any** | The value. |

### Remarks

This method adds worksheet with name AUTO_DATA and adds all values there.  If you use [`ChartDataWorkbook`](/slides/python-net/aspose.slides.charts/chartdataworkbook) to add or edit cell values, be sure that you do not use this worksheet
            Maximum number of values added using this method must not exceed 16711680

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | if limit exceeded |



### See Also
* class [`ChartCategory`](/slides/python-net/aspose.slides.charts/chartcategory)
* class [`ChartCategoryCollection`](/slides/python-net/aspose.slides.charts/chartcategorycollection)
* class [`ChartDataWorkbook`](/slides/python-net/aspose.slides.charts/chartdataworkbook)
* class [`IChartCategory`](/slides/python-net/aspose.slides.charts/ichartcategory)
* class [`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

