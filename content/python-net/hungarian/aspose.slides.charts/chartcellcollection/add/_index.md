---
title: add method
second_title: Aspose.Slides Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Új cellát ad hozzá a gyűjteményhez.


```python
def add(self, cell):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) | Az új hozzáadandó cella. |


## add(self, value) {#any}
Létrehozza a(z) [`ChartDataCell`](/slides/python-net/hu/aspose.slides.charts/chartdatacell)-t a megadott értékből, és hozzáadja a gyűjteményhez.


```python
def add(self, value):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| value | **any** | Az érték. |

### Megjegyzés

Ez a metódus hozzáad egy AUTO_DATA nevű munkalapot, és oda helyezi az összes értéket. Ha a(z) [`ChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/chartdataworkbook)-t használja cellaértékek hozzáadására vagy szerkesztésére, ügyeljen arra, hogy ne használja ezt a munkalapot.
Maximum számú érték, amely ezzel a módszerrel hozzáadható, nem haladhatja meg a 16711680-at

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | ha a limitet túllépte |



### Lásd még
* osztály [`ChartCellCollection`](/slides/python-net/hu/aspose.slides.charts/chartcellcollection)
* osztály [`ChartDataCell`](/slides/python-net/hu/aspose.slides.charts/chartdatacell)
* osztály [`ChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/chartdataworkbook)
* osztály [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)