---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Erstellt eine neue Diagrammreihe und fügt sie der Sammlung hinzu.

### Returns

Neue Diagrammreihe.



```python
def add(self, type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Typ der Reihe |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Erstellt eine neue Diagrammreihe aus [`ChartDataCell`](/slides/python-net/de/aspose.slides.charts/chartdatacell) und fügt sie der Sammlung hinzu.

### Returns

Hinzugefügte Diagrammreihe oder eine Reihe, die bereits in der Sammlung vorhanden ist.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) | Zelle, die den Namen der Reihe enthält. |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Typ, legt den Typ der Reihe fest. |

### Remarks

Wenn eine Diagrammreihe aus derselben Zelle bereits in der Sammlung vorhanden ist, fügt die Methode nichts hinzu und gibt ihren Index zurück.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Erstellt eine neue Diagrammreihe aus [`ChartCellCollection`](/slides/python-net/de/aspose.slides.charts/chartcellcollection) und fügt sie der Sammlung hinzu.

### Returns

Hinzugefügte Diagrammreihe oder eine Reihe, die bereits in der Sammlung vorhanden ist.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/de/aspose.slides.charts/ichartcellcollection) | Zellen, die den Namen der Reihe enthalten. |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Typ, legt den Typ der Reihe fest. |

### Remarks

Wenn eine Diagrammreihe aus derselben Zelle bereits in der Sammlung vorhanden ist, fügt die Methode nichts hinzu und gibt ihren Index zurück.


## add(self, name, type) {#str-charttype}
Erstellt eine neue Diagrammreihe aus dem Wert und fügt sie der Sammlung hinzu.

### Returns

Hinzugefügte Diagrammreihe.



```python
def add(self, name, type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | **str** | Name der Reihe. |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Typ, legt den Typ der Reihe fest. |



### Siehe auch
* Klasse [`ChartCellCollection`](/slides/python-net/de/aspose.slides.charts/chartcellcollection)
* Klasse [`ChartDataCell`](/slides/python-net/de/aspose.slides.charts/chartdatacell)
* Klasse [`ChartSeriesCollection`](/slides/python-net/de/aspose.slides.charts/chartseriescollection)
* Aufzählung [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype)
* Klasse [`IChartCellCollection`](/slides/python-net/de/aspose.slides.charts/ichartcellcollection)
* Klasse [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell)
* Klasse [`IChartSeries`](/slides/python-net/de/aspose.slides.charts/ichartseries)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)