---
title: set_range method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Setzt den Diagrammdatenbereich. Serien und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert.
            Wenn die Anzahl der Serien im Datenbereich größer ist als die Anzahl der Serien in den Diagrammdaten, wird am Ende der Sammlung eine zusätzliche Serie mit demselben Typ wie die letzte Serie der aktuellen Sammlung hinzugefügt.


```python
def set_range(self, formula):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| formula | **str** | Die Zellbereichsformel. z. B.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula ist None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Nicht unterstützter Diagrammtyp |
| **RuntimeError(Proxy error(ArgumentException))** | formula hat ein falsches Format. |



### Siehe auch
* Klasse [`ChartData`](/slides/python-net/de/aspose.slides.charts/chartdata)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)