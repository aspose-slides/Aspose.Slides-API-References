---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartcategorycollection/add/
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
| chart_data_cell | [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) | Cell used to create chart category. |


## add(self, value) {#any}
Erstellt ein neues [`IChartCategory`](/slides/python-net/de/aspose.slides.charts/ichartcategory) aus dem Wert und fügt es der Sammlung hinzu.

### Rückgabewert

Hinzugefügtes [`IChartCategory`](/slides/python-net/de/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | **any** | The value. |

### Bemerkungen

Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und legt dort alle Werte ab. Wenn Sie [`IChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/ichartdataworkbook) verwenden, um Zellwerte hinzuzufügen oder zu bearbeiten, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden. Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden können, darf 16711680 nicht überschreiten

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | if limit exceeded |



### Siehe auch
* class [`IChartCategory`](/slides/python-net/de/aspose.slides.charts/ichartcategory)
* class [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection)
* class [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell)
* class [`IChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)