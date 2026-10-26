---
title: add method
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Dodaj nową komórkę do kolekcji.

```python
def add(self, chart_data_cell):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell) | Nowa komórka do dodania. |

## add(self, value) {#any}
Tworzy [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell) z określonej wartości i dodaje ją do kolekcji.

```python
def add(self, value):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| value | **any** | Wartość. |

### Uwagi

Ta metoda dodaje arkusz o nazwie AUTO_DATA i dodaje tam wszystkie wartości.  Jeśli używasz [`IChartDataWorkbook`](/slides/python-net/pl/aspose.slides.charts/ichartdataworkbook) do dodawania lub edytowania wartości Cell, upewnij się, że nie używasz tego arkusza
            Maksymalna liczba wartości dodawanych przy użyciu tej metody nie może przekraczać 16711680

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | jeśli przekroczono limit |

### Zobacz także
* klasa [`IChartCellCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcellcollection)
* klasa [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell)
* klasa [`IChartDataWorkbook`](/slides/python-net/pl/aspose.slides.charts/ichartdataworkbook)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)