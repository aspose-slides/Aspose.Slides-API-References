---
title: add method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Přidá novou buňku do kolekce.


```python
def add(self, chart_data_cell):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) | Nová buňka k přidání. |


## add(self, value) {#any}
Vytvoří [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) ze zadané hodnoty a přidá ji do kolekce.


```python
def add(self, value):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| value | **any** | Hodnota. |

### Poznámky

Tato metoda přidá list s názvem AUTO_DATA a přidá tam všechny hodnoty.  Pokud používáte [`IChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/ichartdataworkbook) pro přidávání nebo úpravu hodnot buněk, ujistěte se, že tento list nepoužíváte
            Maximální počet hodnot přidaných pomocí této metody nesmí překročit 16711680

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | pokud byl překročen limit |



### Viz také
* třída [`IChartCellCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcellcollection)
* třída [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell)
* třída [`IChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/ichartdataworkbook)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)