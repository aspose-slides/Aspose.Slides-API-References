---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Skapar en ny diagramserie och lägger till den i samlingen.

### Returnerar

Ny diagramserie.



```python
def add(self, type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Type of series |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Skapar en ny diagramserie från [`ChartDataCell`](/slides/python-net/sv/aspose.slides.charts/chartdatacell) och lägger till den i samlingen.

### Returnerar

Tillagd diagramserie eller serie som redan finns i samlingen.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) | Cell which contain series name. |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Type set type of series |

### Anmärkningar

Om diagramserien skapad från samma cell redan finns i samlingen 
            lägger metoden till inget och returnerar dess index.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Skapar en ny diagramserie från [`ChartCellCollection`](/slides/python-net/sv/aspose.slides.charts/chartcellcollection) och lägger till den i samlingen.

### Returnerar

Tillagd diagramserie eller serie som redan finns i samlingen.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcellcollection) | Cells which contain series name. |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Type set type of series |

### Anmärkningar

Om diagramserien skapad från samma cell redan finns i samlingen 
            lägger metoden till inget och returnerar dess index.


## add(self, name, type) {#str-charttype}
Skapar en ny diagramserie från värde och lägger till den i samlingen.

### Returnerar

Tillagd diagramserie.



```python
def add(self, name, type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | **str** | Seriens namn. |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typinställning för serie |



### Se även
* klass [`ChartCellCollection`](/slides/python-net/sv/aspose.slides.charts/chartcellcollection)
* klass [`ChartDataCell`](/slides/python-net/sv/aspose.slides.charts/chartdatacell)
* klass [`ChartSeriesCollection`](/slides/python-net/sv/aspose.slides.charts/chartseriescollection)
* enumeration [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype)
* klass [`IChartCellCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcellcollection)
* klass [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell)
* klass [`IChartSeries`](/slides/python-net/sv/aspose.slides.charts/ichartseries)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)