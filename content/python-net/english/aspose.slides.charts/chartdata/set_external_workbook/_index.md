---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartdata/set_external_workbook/
weight: 20
---


## set_external_workbook {#str}
Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | Path to the target workbook |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.InvalidOperationException** | External workbook is not available or can't be loaded. |



## set_external_workbook {#str-bool}
Sets external workbook as a data source for the chart.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | Path to the target workbook |
| update_chart_data | **bool** | If value is false only workbook path will be updated. <br/><br/>             Chart data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available.<br/><br/>             If value is true chart data will be updated from the target workbook. |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.InvalidOperationException** | External workbook is not available or can't be loaded. |



### See Also
* class [`ChartData`](/slides/python-net/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
