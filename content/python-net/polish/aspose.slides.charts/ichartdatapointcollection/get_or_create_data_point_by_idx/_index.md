---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides dla Pythona via .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Jeśli kolekcja już zawiera punkt danych o indeksie `index`, to zwraca ten punkt danych.
Jeśli kolekcja nie zawiera punktu danych o indeksie `index`==N
(gdy liczba punktów danych w tej kolekcji jest mniejsza lub równa N)
to dodaje brakujące punkty danych i zwraca ostatni (który ma żądany indeks).
Na przykład, indeksy kolekcji to {0, 1, 2}, a żądany indeks to 5.
Wtedy metoda dodaje brakujące punkty danych: {0, 1, 2, 3, 4, 5}. I zwraca punkt danych o indeksie 5.

### Zwraca

Zwraca punkt danych o żądanym indeksie.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks. |



### Zobacz także
* klasa [`IChartDataPoint`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint)
* klasa [`IChartDataPointCollection`](/slides/python-net/pl/aspose.slides.charts/ichartdatapointcollection)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)