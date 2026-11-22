---
title: set_range method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Setzt den Diagrammdatenbereich. Reihen und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert.
Wenn die Anzahl der Reihen im Datenbereich größer ist als die Anzahl der Reihen im Diagrammdaten, wird eine zusätzliche Reihe mit dem gleichen Typ wie die letzte Reihe in der aktuellen Sammlung am Ende der Sammlung hinzugefügt.


```python
def set_range(self, formula):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| formula | **str** | Die Zellen-Datenbereichsformel. Z. B.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula ist None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula hat ein falsches Format. |



### Siehe auch
* Klasse [`IChartData`](/slides/python-net/de/aspose.slides.charts/ichartdata)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)