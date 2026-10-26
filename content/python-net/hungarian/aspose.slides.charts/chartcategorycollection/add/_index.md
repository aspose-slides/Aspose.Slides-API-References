---
title: add method
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Ha a kategória létezik a gyűjteményben, visszaadja. Egyébként új diagramkategóriát hoz létre a(z) [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) alapján, és hozzáadja a gyűjteményhez.

### Visszatérési érték

Hozzáadott vagy meglévő kategória.



```python
def add(self, chart_data_cell):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) | A cella, amely a diagramkategória létrehozásához használatos. |


## add(self, value) {#any}
Új [`ChartCategory`](/slides/python-net/hu/aspose.slides.charts/chartcategory) objektumot hoz létre az értékből, és hozzáadja a gyűjteményhez.

### Visszatérési érték

Hozzáadott [`IChartCategory`](/slides/python-net/hu/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| value | **any** | Az érték. |

### Megjegyzések

Ez a metódus hozzáad egy munkalapot AUTO_DATA névvel, és minden értéket ebbe helyez el. Ha a [`ChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/chartdataworkbook) segítségével ad hozzá vagy szerkeszt cellaértékeket, győződjön meg arról, hogy nem használja ezt a munkalapot. A metódus által hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | ha a határ túllépése |



### Lásd még
* osztály [`ChartCategory`](/slides/python-net/hu/aspose.slides.charts/chartcategory)
* osztály [`ChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/chartcategorycollection)
* osztály [`ChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/chartdataworkbook)
* osztály [`IChartCategory`](/slides/python-net/hu/aspose.slides.charts/ichartcategory)
* osztály [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)