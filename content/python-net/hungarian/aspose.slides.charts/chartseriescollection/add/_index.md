---
title: add method
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Új diagram sorozatot hoz létre, és hozzáadja a gyűjteményhez.

### Visszatérési érték
Új diagram sorozat.

```python
def add(self, type):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype) | A sorozat típusa |

## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Új diagram sorozatot hoz létre [`ChartDataCell`](/slides/python-net/hu/aspose.slides.charts/chartdatacell) alapján, és hozzáadja a gyűjteményhez.

### Visszatérési érték
Hozzáadott diagram sorozat vagy a már a gyűjteményben lévő sorozat.

```python
def add(self, cell_with_series_name, type):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) | A sorozat nevét tartalmazó cella. |
| type | [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype) | A sorozat típusának beállítása. |

### Megjegyzések
Ha a diagram sorozat ugyanabból a cellából származik, amely már a gyűjteményben van, akkor a metódus semmit sem ad hozzá, és visszaadja annak indexét.

## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Új diagram sorozatot hoz létre [`ChartCellCollection`](/slides/python-net/hu/aspose.slides.charts/chartcellcollection) alapján, és hozzáadja a gyűjteményhez.

### Visszatérési érték
Hozzáadott diagram sorozat vagy a már a gyűjteményben lévő sorozat.

```python
def add(self, cells_with_series_name, type):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcellcollection) | A sorozat nevét tartalmazó cellák. |
| type | [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype) | A sorozat típusának beállítása. |

### Megjegyzések
Ha a diagram sorozat ugyanabból a cellából származik, amely már a gyűjteményben van, akkor a metódus semmit sem ad hozzá, és visszaadja annak indexét.

## add(self, name, type) {#str-charttype}
Új diagram sorozatot hoz létre érték alapján, és hozzáadja a gyűjteményhez.

### Visszatérési érték
Hozzáadott diagram sorozat.

```python
def add(self, name, type):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| name | **str** | A sorozat neve. |
| type | [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype) | A sorozat típusának beállítása. |

### Lásd még
* osztály [`ChartCellCollection`](/slides/python-net/hu/aspose.slides.charts/chartcellcollection)
* osztály [`ChartDataCell`](/slides/python-net/hu/aspose.slides.charts/chartdatacell)
* osztály [`ChartSeriesCollection`](/slides/python-net/hu/aspose.slides.charts/chartseriescollection)
* enumeráció [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype)
* osztály [`IChartCellCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcellcollection)
* osztály [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell)
* osztály [`IChartSeries`](/slides/python-net/hu/aspose.slides.charts/ichartseries)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)