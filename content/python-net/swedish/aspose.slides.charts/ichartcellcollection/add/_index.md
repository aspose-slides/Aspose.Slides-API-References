---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Lägg till en ny cell i samlingen.


```python
def add(self, chart_data_cell):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) | Ny cell att lägga till. |


## add(self, value) {#any}
Skapar [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) från angivet värde och lägger till det i samlingen.


```python
def add(self, value):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | **any** | Värdet. |

### Anmärkningar

Denna metod lägger till ett kalkylblad med namn AUTO_DATA och lägger alla värden där.  Om du använder [`IChartDataWorkbook`](/slides/python-net/sv/aspose.slides.charts/ichartdataworkbook) för att lägga till eller redigera Cell värden, se till att du inte använder detta kalkylblad
            Det maximala antalet värden som läggs till med den här metoden får inte överstiga 16711680

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | om gränsen överskrids |



### Se även
* klass [`IChartCellCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcellcollection)
* klass [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell)
* klass [`IChartDataWorkbook`](/slides/python-net/sv/aspose.slides.charts/ichartdataworkbook)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)