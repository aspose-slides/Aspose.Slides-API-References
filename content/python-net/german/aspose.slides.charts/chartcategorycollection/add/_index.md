---
title: add method
second_title: Aspose.Slides für Python via .NET API Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) erstellt und zur Sammlung hinzugefügt.

### Rückgabewert

Hinzugefügte oder vorhandene Kategorie.



```python
def add(self, chart_data_cell):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) | Zelle, die zur Erstellung der Diagrammkategorie verwendet wird. |


## add(self, value) {#any}
Erstellt ein neues [`ChartCategory`](/slides/python-net/de/aspose.slides.charts/chartcategory) aus dem Wert und fügt es der Sammlung hinzu.

### Rückgabewert

Hinzugefügt [`IChartCategory`](/slides/python-net/de/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | **any** | Der Wert. |

### Bemerkungen

Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und schreibt dort alle Werte hinein.  Wenn Sie [`ChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/chartdataworkbook) zum Hinzufügen oder Bearbeiten von Zellwerten verwenden, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht benutzen.  Die maximale Anzahl von über diese Methode hinzugefügten Werten darf 16711680 nicht überschreiten.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | wenn das Limit überschritten wird |



### Siehe auch
* Klasse [`ChartCategory`](/slides/python-net/de/aspose.slides.charts/chartcategory)
* Klasse [`ChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/chartcategorycollection)
* Klasse [`ChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/chartdataworkbook)
* Klasse [`IChartCategory`](/slides/python-net/de/aspose.slides.charts/ichartcategory)
* Klasse [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)