---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Fügt der Sammlung eine neue Zelle hinzu.

```python
def add(self, chart_data_cell):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) | Neue Zelle zum Hinzufügen. |

## add(self, value) {#any}
Erstellt [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) aus dem angegebenen Wert und fügt ihn zur Sammlung hinzu.

```python
def add(self, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | **any** | Der Wert. |

### Anmerkungen
Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und fügt dort alle Werte ein. Wenn Sie [`IChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/ichartdataworkbook) verwenden, um Zellenwerte hinzuzufügen oder zu bearbeiten, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden
            Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden können, darf 16711680 nicht überschreiten

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | wenn das Limit überschritten wird |

### Siehe auch
* Klasse [`IChartCellCollection`](/slides/python-net/de/aspose.slides.charts/ichartcellcollection)
* Klasse [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell)
* Klasse [`IChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/ichartdataworkbook)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)