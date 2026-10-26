---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Om kategorin finns i samlingen, returneras den. Annars skapas en ny diagramkategori från 
            [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) och läggs till i samlingen.

### Returns
Tillagd eller befintlig kategori.



```python
def add(self, chart_data_cell):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) | Cell som används för att skapa diagramkategorin. |


## add(self, value) {#any}
Skapar ny [`ChartCategory`](/slides/python-net/sv/aspose.slides.charts/chartcategory) från värdet och lägger till den i samlingen.

### Returns
Tillagd [`IChartCategory`](/slides/python-net/sv/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | **any** | Värdet. |

### Remarks
Denna metod lägger till ett arbetsblad med namn AUTO_DATA och lägger till alla värden där.  Om du använder [`ChartDataWorkbook`](/slides/python-net/sv/aspose.slides.charts/chartdataworkbook) för att lägga till eller redigera cellvärden, se till att du inte använder detta arbetsblad
            Maximalt antal värden som läggs till med denna metod får inte överstiga 16711680

### Exceptions

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | om gränsen överskrids |



### See Also
* klass [`ChartCategory`](/slides/python-net/sv/aspose.slides.charts/chartcategory)
* klass [`ChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/chartcategorycollection)
* klass [`ChartDataWorkbook`](/slides/python-net/sv/aspose.slides.charts/chartdataworkbook)
* klass [`IChartCategory`](/slides/python-net/sv/aspose.slides.charts/ichartcategory)
* klass [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)