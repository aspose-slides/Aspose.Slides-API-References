---
title: set_external_workbook method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Legt ein externes Arbeitsbuch als Datenquelle für das Diagramm fest. Diagrammdaten werden aus dem Zielarbeitsbuch aktualisiert.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| workbook_path | **str** | Pfad zum Zielarbeitsbuch |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externes Arbeitsbuch ist nicht verfügbar oder kann nicht geladen werden. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Legt ein externes Arbeitsbuch als Datenquelle für das Diagramm fest.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| workbook_path | **str** | Pfad zum Zielarbeitsbuch |
| update_chart_data | **bool** | Wenn der Wert false ist, wird nur der Pfad zum Arbeitsbuch aktualisiert.<br/><br/>Diagrammdaten werden nicht aus dem Zielarbeitsbuch geladen und aktualisiert. Kann verwendet werden, wenn das Zielarbeitsbuch nicht existiert oder nicht verfügbar ist.<br/><br/>Wenn der Wert true ist, werden die Diagrammdaten aus dem Zielarbeitsbuch aktualisiert. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externes Arbeitsbuch ist nicht verfügbar oder kann nicht geladen werden. |



### Siehe auch
* Klasse [`ChartData`](/slides/python-net/de/aspose.slides.charts/chartdata)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)