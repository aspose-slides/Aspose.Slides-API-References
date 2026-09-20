---
title: add method
second_title: Aspose.Slides pro Python přes .NET – referenční příručka API
description: 
type: docs
url: /cs/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Přidejte novou buňku do kolekce.

```python
def add(self, cell):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) | Nová buňka k přidání. |

## add(self, value) {#any}
Vytvoří [`ChartDataCell`](/slides/python-net/cs/aspose.slides.charts/chartdatacell) ze zadané hodnoty a přidá jej do kolekce.

```python
def add(self, value):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| value | **any** | Hodnota. |

### Poznámky
Tato metoda přidá list s názvem AUTO_DATA a přidá tam všechny hodnoty.  Pokud používáte [`ChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/chartdataworkbook) k přidání nebo úpravě hodnot buněk, ujistěte se, že tento list nepoužíváte.
            Maximální počet hodnot přidaných pomocí této metody nesmí překročit 16711680

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | pokud je limit překročen |

### Viz také
* class [`ChartCellCollection`](/slides/python-net/cs/aspose.slides.charts/chartcellcollection)
* class [`ChartDataCell`](/slides/python-net/cs/aspose.slides.charts/chartdatacell)
* class [`ChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/chartdataworkbook)
* class [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell)
* module [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)