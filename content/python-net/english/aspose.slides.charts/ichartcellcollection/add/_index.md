---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartcellcollection/add/
weight: 10
---


## add {#ichartdatacell}
Add new cell to the collection.


```python
def add(self, chart_data_cell):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell) | New cell to add. |


## add {#any}
Creates [`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell) from specified value and adds it to the collection.


```python
def add(self, value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| value | **any** | The value. |

### Remarks

This method adds worksheet with name AUTO_DATA and adds all values there.  If you use [`IChartDataWorkbook`](/slides/python-net/aspose.slides.charts/ichartdataworkbook) to add or edit Cell values, be sure that you do not use this worksheet
            Maximum number of values added using this method must not exceed 16711680

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | if limit exceeded |



### See Also
* class [`IChartCellCollection`](/slides/python-net/aspose.slides.charts/ichartcellcollection)
* class [`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell)
* class [`IChartDataWorkbook`](/slides/python-net/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

