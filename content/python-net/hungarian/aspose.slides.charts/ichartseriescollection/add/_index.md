---
title: add method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartseriescollection/add/
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
| type | [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype) | Sorozat típusa |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Új diagram sorozatot hoz létre a(z) [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) alapján, és hozzáadja a gyűjteményhez.

### Visszatérési érték

Hozzáadott diagram sorozat, vagy egy már a gyűjteményben lévő sorozat.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) | Cella, amely a sorozat nevét tartalmazza. |
| type | [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype) | A sorozat típusának beállítása |

### Megjegyzés

Ha a diagram sorozat már létezik ugyanabból a cellából a gyűjteményben, a módszer nem ad hozzá semmit, és visszaadja annak indexét.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Új diagram sorozatot hoz létre a(z) [`IChartCellCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcellcollection) alapján, és hozzáadja a gyűjteményhez.

### Visszatérési érték

Hozzáadott diagram sorozat, vagy egy már a gyűjteményben lévő sorozat.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcellcollection) | Cellák, amelyek a sorozat nevét tartalmazzák. |
| type | [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype) | A sorozat típusának beállítása |

### Megjegyzés

Ha a diagram sorozat már létezik ugyanabból a cellából a gyűjteményben, a módszer nem ad hozzá semmit, és visszaadja annak indexét.


## add(self, name, type) {#str-charttype}
Új diagram sorozatot hoz létre az érték alapján, és hozzáadja a gyűjteményhez.

### Visszatérési érték

Hozzáadott diagram sorozat.



```python
def add(self, name, type):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| name | **str** | Sorozat neve. |
| type | [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype) | A sorozat típusának beállítása |



### Lásd még
* enumeráció [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype)
* osztály [`IChartCellCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcellcollection)
* osztály [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell)
* osztály [`IChartSeries`](/slides/python-net/hu/aspose.slides.charts/ichartseries)
* osztály [`IChartSeriesCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriescollection)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)