---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Lägg till en ny cell i samlingen.

```python
def add(self, cell):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) | Ny cell att lägga till. |

## add(self, value) {#any}
Skapar [`ChartDataCell`](/slides/python-net/sv/aspose.slides.charts/chartdatacell) från angivet värde och lägger till det i samlingen.

```python
def add(self, value):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | **any** | Värdet. |

### Anmärkningar

Denna metod lägger till ett kalkylblad med namnet AUTO_DATA och lägger till alla värden där.  Om du använder [`ChartDataWorkbook`](/slides/python-net/sv/aspose.slides.charts/chartdataworkbook) för att lägga till eller redigera Cell-värden, se till att du inte använder detta kalkylblad
            Maximalt antal värden som kan läggas till med denna metod får inte överstiga 16711680

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | om gränsen överskrids |

### Se också
* klass [`ChartCellCollection`](/slides/python-net/sv/aspose.slides.charts/chartcellcollection)
* klass [`ChartDataCell`](/slides/python-net/sv/aspose.slides.charts/chartdatacell)
* klass [`ChartDataWorkbook`](/slides/python-net/sv/aspose.slides.charts/chartdataworkbook)
* klass [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)