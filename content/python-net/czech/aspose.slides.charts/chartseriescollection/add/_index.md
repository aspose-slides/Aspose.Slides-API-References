---
title: add method
second_title: Aspose.Slides pro Python pomocí .NET referenční příručky API
description: 
type: docs
url: /cs/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Vytvoří novou sérii grafu a přidá ji do kolekce.

### Návratová hodnota

Nová série grafu.



```python
def add(self, type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ řady |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Vytvoří novou sérii grafu z [`ChartDataCell`](/slides/python-net/cs/aspose.slides.charts/chartdatacell) a přidá ji do kolekce.

### Návratová hodnota

Přidaná série grafu nebo série, která již v kolekci existuje.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) | Buňka, která obsahuje název řady. |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ nastavení řady |

### Poznámky

Pokud je série grafu vytvořena ze stejné buňky, která již v kolekci je, metoda nic nepřidá a vrátí její index.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Vytvoří novou sérii grafu z [`ChartCellCollection`](/slides/python-net/cs/aspose.slides.charts/chartcellcollection) a přidá ji do kolekce.

### Návratová hodnota

Přidaná série grafu nebo série, která již v kolekci existuje.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcellcollection) | Buňky, které obsahují název řady. |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ nastavení řady |

### Poznámky

Pokud je série grafu vytvořena ze stejné buňky, která již v kolekci je, metoda nic nepřidá a vrátí její index.


## add(self, name, type) {#str-charttype}
Vytvoří novou sérii grafu z hodnoty a přidá ji do kolekce.

### Návratová hodnota

Přidaná série grafu.



```python
def add(self, name, type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| name | **str** | Název řady. |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ nastavení řady |



### Viz také
* třída [`ChartCellCollection`](/slides/python-net/cs/aspose.slides.charts/chartcellcollection)
* třída [`ChartDataCell`](/slides/python-net/cs/aspose.slides.charts/chartdatacell)
* třída [`ChartSeriesCollection`](/slides/python-net/cs/aspose.slides.charts/chartseriescollection)
* výčtový typ [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype)
* třída [`IChartCellCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcellcollection)
* třída [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell)
* třída [`IChartSeries`](/slides/python-net/cs/aspose.slides.charts/ichartseries)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)