---
title: add method
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Tworzy nową serię wykresu i dodaje ją do kolekcji.

### Returns

Dodana seria wykresu.



```python
def add(self, type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ serii |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Tworzy nową serię wykresu z [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell) i dodaje ją do kolekcji.

### Returns

Dodana seria wykresu lub seria, która już jest w kolekcji.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell) | Komórka zawierająca nazwę serii. |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ ustawia typ serii |

### Remarks

Jeśli seria wykresu utworzona z tej samej komórki już znajduje się w kolekcji, metoda nie dodaje nic i zwraca jej indeks.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Tworzy nową serię wykresu z [`IChartCellCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcellcollection) i dodaje ją do kolekcji.

### Returns

Dodana seria wykresu lub seria, która już jest w kolekcji.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcellcollection) | Komórki zawierające nazwę serii. |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ ustawia typ serii |

### Remarks

Jeśli seria wykresu utworzona z tej samej komórki już znajduje się w kolekcji, metoda nie dodaje nic i zwraca jej indeks.


## add(self, name, type) {#str-charttype}
Tworzy nową serię wykresu z wartości i dodaje ją do kolekcji.

### Returns

Dodana seria wykresu.



```python
def add(self, name, type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| name | **str** | Nazwa serii. |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ ustawia typ serii |



### See Also
* enumeracja [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype)
* klasa [`IChartCellCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcellcollection)
* klasa [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell)
* klasa [`IChartSeries`](/slides/python-net/pl/aspose.slides.charts/ichartseries)
* klasa [`IChartSeriesCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriescollection)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)