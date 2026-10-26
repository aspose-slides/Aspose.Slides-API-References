---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Om kategori finns i samlingen, returneras den. Annars skapas en ny diagramkategori från [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) och läggs till i samlingen.

### Returnerar

Tillagd eller befintlig kategori.



```python
def add(self, chart_data_cell):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) | Cell som används för att skapa diagramkategori. |


## add(self, value) {#any}
Skapar en ny [`IChartCategory`](/slides/python-net/sv/aspose.slides.charts/ichartcategory) från värdet och lägger till den i samlingen.

### Returnerar

Tillagd [`IChartCategory`](/slides/python-net/sv/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | **any** | Värdet. |

### Anmärkningar

Denna metod lägger till ett kalkylblad med namnet AUTO_DATA och lägger till alla värden där. Om du använder [`IChartDataWorkbook`](/slides/python-net/sv/aspose.slides.charts/ichartdataworkbook) för att lägga till eller redigera cellvärden, se till att du inte använder detta kalkylblad. Maximalt antal värden som läggs till med denna metod får inte överstiga 16711680

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | om gränsen överskrids |



### Se även
* class [`IChartCategory`](/slides/python-net/sv/aspose.slides.charts/ichartcategory)
* class [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection)
* class [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell)
* class [`IChartDataWorkbook`](/slides/python-net/sv/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)