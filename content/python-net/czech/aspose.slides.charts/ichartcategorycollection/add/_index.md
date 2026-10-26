---
title: add method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Pokud kategorie v kolekci existuje, vrátí ji. Jinak vytvoří novou kategorii grafu z 
            [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) a přidá ji do kolekce.

### Návratová hodnota

Přidaná nebo existující kategorie.



```python
def add(self, chart_data_cell):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) | Buňka použitá k vytvoření kategorie grafu. |


## add(self, value) {#any}
Vytvoří nový [`IChartCategory`](/slides/python-net/cs/aspose.slides.charts/ichartcategory) z hodnoty a přidá jej do kolekce.

### Návratová hodnota

Přidáno [`IChartCategory`](/slides/python-net/cs/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| value | **any** | Hodnota. |

### Poznámky

Tato metoda přidá list s názvem AUTO_DATA a přidá do něj všechny hodnoty.  Pokud použijete [`IChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/ichartdataworkbook) k přidání nebo úpravě hodnot buněk, ujistěte se, že tento list nepoužijete.
Maximum počet hodnot přidaných touto metodou nesmí překročit 16711680

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | pokud byl překročen limit |



### Viz také
* třída [`IChartCategory`](/slides/python-net/cs/aspose.slides.charts/ichartcategory)
* třída [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection)
* třída [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell)
* třída [`IChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/ichartdataworkbook)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)