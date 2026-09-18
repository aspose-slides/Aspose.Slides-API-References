---
title: add method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Dodaj nową komórkę do kolekcji.


```python
def add(self, cell):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell) | Nowa komórka do dodania. |


## add(self, value) {#any}
Tworzy [`ChartDataCell`](/slides/python-net/pl/aspose.slides.charts/chartdatacell) z określonej wartości i dodaje go do kolekcji.


```python
def add(self, value):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| value | **any** | Wartość. |

### Uwagi

Ta metoda dodaje arkusz kalkulacyjny o nazwie AUTO_DATA i dodaje tam wszystkie wartości. Jeśli używasz [`ChartDataWorkbook`](/slides/python-net/pl/aspose.slides.charts/chartdataworkbook) do dodawania lub edytowania wartości komórek, upewnij się, że nie używasz tego arkusza kalkulacyjnego. Maksymalna liczba wartości dodawanych przy użyciu tej metody nie może przekroczyć 16711680

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | jeśli przekroczono limit |



### Zobacz także
* klasa [`ChartCellCollection`](/slides/python-net/pl/aspose.slides.charts/chartcellcollection)
* klasa [`ChartDataCell`](/slides/python-net/pl/aspose.slides.charts/chartdatacell)
* klasa [`ChartDataWorkbook`](/slides/python-net/pl/aspose.slides.charts/chartdataworkbook)
* klasa [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)