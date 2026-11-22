---
title: set_external_workbook method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Legt die externe Arbeitsmappe als Datenquelle für das Diagramm fest. Die Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| workbook_path | **str** | Pfad zur Zielarbeitsmappe |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externe Arbeitsmappe ist nicht verfügbar oder kann nicht geladen werden. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Legt die externe Arbeitsmappe als Datenquelle für das Diagramm fest.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| workbook_path | **str** | Pfad zur Zielarbeitsmappe |
| update_chart_data | **bool** | Wenn der Wert false ist, wird nur der Pfad zur Arbeitsmappe aktualisiert. <br/><br/> Diagrammdaten werden nicht aus der Zielarbeitsmappe geladen und aktualisiert. Kann verwendet werden, wenn die Zielarbeitsmappe nicht existiert oder nicht verfügbar ist.<br/><br/> Wenn der Wert true ist, werden die Diagrammdaten aus der Zielarbeitsmappe aktualisiert. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externe Arbeitsmappe ist nicht verfügbar oder kann nicht geladen werden. |



### Siehe auch
* Klasse [`ChartData`](/slides/python-net/de/aspose.slides.charts/chartdata)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)