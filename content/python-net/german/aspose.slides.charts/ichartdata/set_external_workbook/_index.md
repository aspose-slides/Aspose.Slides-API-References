---
title: set_external_workbook method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| workbook_path | **str** | Pfad zur Zielarbeitsmappe |

### Ausnahmen

| Exception | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externe Arbeitsmappe ist nicht verfügbar oder kann nicht geladen werden. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| workbook_path | **str** | Pfad zur Zielarbeitsmappe |
| update_chart_data | **bool** | Wenn der Wert false ist, wird nur der Pfad der Arbeitsmappe aktualisiert. <br/><br/>             Diagrammdaten werden nicht aus der Zielarbeitsmappe geladen und aktualisiert. Kann verwendet werden, wenn die Zielarbeitsmappe nicht existiert oder nicht verfügbar ist.<br/><br/>             Wenn der Wert true ist, werden Diagrammdaten aus der Zielarbeitsmappe aktualisiert. |

### Ausnahmen

| Exception | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externe Arbeitsmappe ist nicht verfügbar oder kann nicht geladen werden. |



### Siehe auch
* Klasse [`IChartData`](/slides/python-net/de/aspose.slides.charts/ichartdata)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)