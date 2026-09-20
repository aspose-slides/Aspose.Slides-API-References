---
title: add method
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Pokud kategorie v kolekci existuje, vrátí ji. Jinak vytvoří novou kategorii grafu z [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) a přidá ji do kolekce.

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
Vytvoří nový [`ChartCategory`](/slides/python-net/cs/aspose.slides.charts/chartcategory) z hodnoty a přidá ho do kolekce.

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
Tato metoda přidá list s názvem AUTO_DATA a přidá do něj všechny hodnoty.  Pokud používáte [`ChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/chartdataworkbook) k přidávání nebo úpravě hodnot buněk, ujistěte se, že tento list nepoužíváte
            Maximální počet hodnot přidaných pomocí této metody nesmí překročit 16711680

### Výjimky
| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | pokud je limit překročen |

### Viz také
* třída [`ChartCategory`](/slides/python-net/cs/aspose.slides.charts/chartcategory)
* třída [`ChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/chartcategorycollection)
* třída [`ChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/chartdataworkbook)
* třída [`IChartCategory`](/slides/python-net/cs/aspose.slides.charts/ichartcategory)
* třída [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)