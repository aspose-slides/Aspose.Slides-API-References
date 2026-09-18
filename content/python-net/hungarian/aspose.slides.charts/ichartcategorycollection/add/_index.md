---
title: add method
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Ha a kategória létezik a gyűjteményben, visszaadja. Egyébként új diagramkategóriát hoz létre a 
            [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) alapján, és hozzáadja a gyűjteményhez.

### Visszatér

Hozzáadott vagy már létező kategória.



```python
def add(self, chart_data_cell):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) | A cella, amely a diagramkategória létrehozásához használatos. |


## add(self, value) {#any}
Új [`IChartCategory`](/slides/python-net/hu/aspose.slides.charts/ichartcategory)-t hoz létre az értékből, és hozzáadja a gyűjteményhez.

### Visszatér

Hozzáadott [`IChartCategory`](/slides/python-net/hu/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| value | **any** | Az érték. |

### Megjegyzés

Ez a metódus hozzáad egy AUTO_DATA nevű munkalapot, és minden értéket oda helyez.  Ha a [`IChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/ichartdataworkbook)-t használja cellaértékek hozzáadására vagy szerkesztésére, ügyeljen arra, hogy ne használja ezt a munkalapot
            A módszerrel hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | ha a limit átlépésre kerül |



### Lásd még
* osztály [`IChartCategory`](/slides/python-net/hu/aspose.slides.charts/ichartcategory)
* osztály [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection)
* osztály [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell)
* osztály [`IChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/ichartdataworkbook)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)