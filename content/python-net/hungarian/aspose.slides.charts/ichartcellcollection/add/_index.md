---
title: add method
second_title: Aspose.Slides a Python számára .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Új cellát ad a gyűjteményhez.

```python
def add(self, chart_data_cell):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) | Új cella, amelyet hozzáad. |

## add(self, value) {#any}
Létrehozza a(z) [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell)-t a megadott értékből, és hozzáadja a gyűjteményhez.

```python
def add(self, value):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| value | **any** | Az érték. |

### Megjegyzések

Ez a metódus hozzáad egy munkalapot AUTO_DATA névvel, és oda helyezi az összes értéket. Ha a(z) [`IChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/ichartdataworkbook)-t használja cellaértékek hozzáadására vagy szerkesztésére, ügyeljen arra, hogy ne használja ezt a munkalapot.
A módszerrel hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at.

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | ha a limit túllépésre kerül |

### Lásd még
* osztály [`IChartCellCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcellcollection)
* osztály [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell)
* osztály [`IChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/ichartdataworkbook)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)