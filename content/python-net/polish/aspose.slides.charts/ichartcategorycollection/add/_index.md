---
title: add method
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Jeśli kategoria istnieje w kolekcji, zwróć ją. W przeciwnym razie tworzy nową kategorię wykresu z [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell) i dodaje ją do kolekcji.

### Zwraca

Dodana lub istniejąca kategoria.



```python
def add(self, chart_data_cell):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell) | Cell używana do tworzenia kategorii wykresu. |


## add(self, value) {#any}
Tworzy nowy [`IChartCategory`](/slides/python-net/pl/aspose.slides.charts/ichartcategory) z wartości i dodaje go do kolekcji.

### Zwraca

Dodano [`IChartCategory`](/slides/python-net/pl/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| value | **any** | Wartość. |

### Uwagi

Ta metoda dodaje arkusz kalkulacyjny o nazwie AUTO_DATA i dodaje do niego wszystkie wartości. Jeśli używasz [`IChartDataWorkbook`](/slides/python-net/pl/aspose.slides.charts/ichartdataworkbook) do dodawania lub edytowania wartości komórek, upewnij się, że nie używasz tego arkusza.
Maksymalna liczba wartości dodawanych przy użyciu tej metody nie może przekroczyć 16711680

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | jeśli przekroczono limit |



### Zobacz także
* klasa [`IChartCategory`](/slides/python-net/pl/aspose.slides.charts/ichartcategory)
* klasa [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection)
* klasa [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell)
* klasa [`IChartDataWorkbook`](/slides/python-net/pl/aspose.slides.charts/ichartdataworkbook)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)