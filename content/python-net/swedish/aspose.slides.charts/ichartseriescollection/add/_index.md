---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartseriescollection/add/
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
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typ av serie |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Skapar en ny diagramserie från [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) och lägger till den i samlingen.

### Returnerar

Tillagd diagramserie eller serie som redan finns i samlingen.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) | Cell som innehåller serienamnet. |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typ av serie som ska sättas |

### Anmärkningar

Om diagramserien skapades från samma cell som redan finns i samlingen 
            lägger metoden till ingenting och returnerar dess index.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Skapar en ny diagramserie från [`IChartCellCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcellcollection) och lägger till den i samlingen.

### Returnerar

Tillagd diagramserie eller serie som redan finns i samlingen.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcellcollection) | Celler som innehåller serienamn. |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typ av serie som ska sättas |

### Anmärkningar

Om diagramserien skapades från samma cell som redan finns i samlingen 
            lägger metoden till ingenting och returnerar dess index.


## add(self, name, type) {#str-charttype}
Skapar en ny diagramserie från värdet och lägger till den i samlingen.

### Returnerar

Tillagd diagramserie.



```python
def add(self, name, type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | **str** | Serienamn. |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typ av serie som ska sättas |



### Se även
* enumeration [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype)
* klass [`IChartCellCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcellcollection)
* klass [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell)
* klass [`IChartSeries`](/slides/python-net/sv/aspose.slides.charts/ichartseries)
* klass [`IChartSeriesCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriescollection)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)