---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartcellcollection/add/
weight: 10
---


## add {#asposeslideschartsichartdatacell}
Add new cell to the collection.


```python
def add(self, cell):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell) | New cell to add. |


## add {#any}
Creates [`ChartDataCell`](/slides/python-net/aspose.slides.charts/chartdatacell) from specified value and adds it to the collection.


```python
def add(self, value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| value | **any** | The value. |

### Remarks

This method adds worksheet with name AUTO_DATA and adds all values there.  If you use [`ChartDataWorkbook`](/slides/python-net/aspose.slides.charts/chartdataworkbook) to add or edit Cell values, be sure that you do not use this worksheet
            Maximum number of values added using this method must not exceed 16711680

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | if limit exceeded |



### See Also
* class [`ChartCellCollection`](/slides/python-net/aspose.slides.charts/chartcellcollection)
* class [`ChartDataCell`](/slides/python-net/aspose.slides.charts/chartdatacell)
* class [`ChartDataWorkbook`](/slides/python-net/aspose.slides.charts/chartdataworkbook)
* class [`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

