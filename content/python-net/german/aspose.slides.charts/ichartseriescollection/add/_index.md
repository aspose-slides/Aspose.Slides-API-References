---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Erstellt eine neue Diagrammserie und fügt sie der Sammlung hinzu.

### Rückgabewert

Neue Diagrammserie.



```python
def add(self, type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Typ der Serie |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Erstellt eine neue Diagrammserie aus [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) und fügt sie der Sammlung hinzu.

### Rückgabewert

Hinzugefügte Diagrammserie oder bereits in der Sammlung vorhandene Serie.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) | Zelle, die den Seriennamen enthält. |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Typ der Serie festlegen |

### Anmerkungen

Wenn eine Diagrammserie, die aus derselben Zelle stammt, bereits in der Sammlung ist, dann fügt die Methode nichts hinzu und gibt ihren Index zurück.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Erstellt eine neue Diagrammserie aus [`IChartCellCollection`](/slides/python-net/de/aspose.slides.charts/ichartcellcollection) und fügt sie der Sammlung hinzu.

### Rückgabewert

Hinzugefügte Diagrammserie oder bereits in der Sammlung vorhandene Serie.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/de/aspose.slides.charts/ichartcellcollection) | Zellen, die den Seriennamen enthalten. |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Typ der Serie festlegen |

### Anmerkungen

Wenn eine Diagrammserie, die aus derselben Zelle stammt, bereits in der Sammlung ist, dann fügt die Methode nichts hinzu und gibt ihren Index zurück.


## add(self, name, type) {#str-charttype}
Erstellt eine neue Diagrammserie aus dem Wert und fügt sie der Sammlung hinzu.

### Rückgabewert

Hinzugefügte Diagrammserie.



```python
def add(self, name, type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | **str** | Serienname. |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Typ der Serie festlegen |



### Siehe auch
* Aufzählung [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype)
* Klasse [`IChartCellCollection`](/slides/python-net/de/aspose.slides.charts/ichartcellcollection)
* Klasse [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell)
* Klasse [`IChartSeries`](/slides/python-net/de/aspose.slides.charts/ichartseries)
* Klasse [`IChartSeriesCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriescollection)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)