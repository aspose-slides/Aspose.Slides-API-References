---
title: add method
second_title: Aspose.Slides pro Python přes .NET API Referenční příručka
description: 
type: docs
url: /cs/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Vytvoří novou sérii grafu a přidá ji do kolekce.

### Vrací

Nová série grafu.



```python
def add(self, type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ série |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Vytvoří novou sérii grafu z [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) a přidá ji do kolekce.

### Vrací

Přidaná série grafu nebo série, která již je v kolekci.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) | Buňka, která obsahuje název série. |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ nastavení typu série |

### Poznámky

Pokud je série grafu vytvořena ze stejné buňky, která již je v kolekci, metoda nic nepřidá a vrátí její index.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Vytvoří novou sérii grafu z [`IChartCellCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcellcollection) a přidá ji do kolekce.

### Vrací

Přidaná série grafu nebo série, která již je v kolekci.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcellcollection) | Buňky, které obsahují název série. |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ nastavení typu série |

### Poznámky

Pokud je série grafu vytvořena ze stejné buňky, která již je v kolekci, metoda nic nepřidá a vrátí její index.


## add(self, name, type) {#str-charttype}
Vytvoří novou sérii grafu z hodnoty a přidá ji do kolekce.

### Vrací

Přidaná série grafu.



```python
def add(self, name, type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| name | **str** | Název série. |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ nastavení typu série |



### Viz také
* enumerace [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype)
* třída [`IChartCellCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcellcollection)
* třída [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell)
* třída [`IChartSeries`](/slides/python-net/cs/aspose.slides.charts/ichartseries)
* třída [`IChartSeriesCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriescollection)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)