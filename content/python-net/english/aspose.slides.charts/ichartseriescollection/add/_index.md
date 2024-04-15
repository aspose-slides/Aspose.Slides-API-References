---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartseriescollection/add/
weight: 10
---


## add {#charttype}
Creates new chart series and adds it to the collection.

### Returns

New chart series.



```python
def add(self, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | ChartType | Type of series |



## add {#ichartdatacell-charttype}
Creates new chart series from [`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell) and adds it to the collection.

### Returns

Added chart series or series that already is in collection.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cell_with_series_name | IChartDataCell | Cell which contain series name. |
| type | ChartType | Type set type of series |

### Remarks

If chart series careted from same cell already in collection 
            then method adds nothing and returns it's index.



## add {#ichartcellcollection-charttype}
Creates new chart series from [`IChartCellCollection`](/slides/python-net/aspose.slides.charts/ichartcellcollection) and adds it to the collection.

### Returns

Added chart series or series that already is in collection.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cells_with_series_name | IChartCellCollection | Cells which contain series name. |
| type | ChartType | Type set type of series |

### Remarks

If chart series careted from same cell already in collection 
            then method adds nothing and returns it's index.



## add {#string-charttype}
Creates new chart series from value and adds it to the collection.

### Returns

Added chart series.



```python
def add(self, name, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| name | string | Series name. |
| type | ChartType | Type set type of series |



### See Also
* class [`IChartCellCollection`](/slides/python-net/aspose.slides.charts/ichartcellcollection)
* class [`IChartDataCell`](/slides/python-net/aspose.slides.charts/ichartdatacell)
* class [`IChartSeriesCollection`](/slides/python-net/aspose.slides.charts/ichartseriescollection)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
