---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Fügt neue Zelle zur Sammlung hinzu.


```python
def add(self, cell):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) | Neue Zelle zum Hinzufügen. |


## add(self, value) {#any}
Erstellt [`ChartDataCell`](/slides/python-net/de/aspose.slides.charts/chartdatacell) aus dem angegebenen Wert und fügt ihn zur Sammlung hinzu.


```python
def add(self, value):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | **any** | Der Wert. |

### Anmerkungen

Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und fügt dort alle Werte ein.  Wenn Sie [`ChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/chartdataworkbook) verwenden, um Cell values hinzuzufügen oder zu bearbeiten, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden
            Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden kann, darf 16711680 nicht überschreiten

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | wenn das Limit überschritten wird |



### Siehe auch
* Klasse [`ChartCellCollection`](/slides/python-net/de/aspose.slides.charts/chartcellcollection)
* Klasse [`ChartDataCell`](/slides/python-net/de/aspose.slides.charts/chartdatacell)
* Klasse [`ChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/chartdataworkbook)
* Klasse [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)