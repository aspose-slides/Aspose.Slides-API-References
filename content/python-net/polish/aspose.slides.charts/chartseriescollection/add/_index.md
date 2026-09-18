---
title: add method
second_title: Aspose.Slides dla Pythona via .NET - Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Tworzy nową serię wykresu i dodaje ją do kolekcji.

### Zwraca

Nowa seria wykresu.



```python
def add(self, type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Type of series |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Tworzy nową serię wykresu z [`ChartDataCell`](/slides/python-net/pl/aspose.slides.charts/chartdatacell) i dodaje ją do kolekcji.

### Zwraca

Dodana seria wykresu lub seria, która już znajduje się w kolekcji.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell) | Komórka zawierająca nazwę serii. |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ ustawiony dla serii |

### Uwagi

Jeśli seria wykresu utworzona z tej samej komórki już znajduje się w kolekcji 
            wtedy metoda nie dodaje nic i zwraca jej indeks.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Tworzy nową serię wykresu z [`ChartCellCollection`](/slides/python-net/pl/aspose.slides.charts/chartcellcollection) i dodaje ją do kolekcji.

### Zwraca

Dodana seria wykresu lub seria, która już znajduje się w kolekcji.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcellcollection) | Komórki zawierające nazwę serii. |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ ustawiony dla serii |

### Uwagi

Jeśli seria wykresu utworzona z tej samej komórki już znajduje się w kolekcji 
            wtedy metoda nie dodaje nic i zwraca jej indeks.


## add(self, name, type) {#str-charttype}
Tworzy nową serię wykresu z wartości i dodaje ją do kolekcji.

### Zwraca

Dodana seria wykresu.



```python
def add(self, name, type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| name | **str** | Nazwa serii. |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ ustawiony dla serii |



### Zobacz także
* klasa [`ChartCellCollection`](/slides/python-net/pl/aspose.slides.charts/chartcellcollection)
* klasa [`ChartDataCell`](/slides/python-net/pl/aspose.slides.charts/chartdatacell)
* klasa [`ChartSeriesCollection`](/slides/python-net/pl/aspose.slides.charts/chartseriescollection)
* enumeracja [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype)
* klasa [`IChartCellCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcellcollection)
* klasa [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell)
* klasa [`IChartSeries`](/slides/python-net/pl/aspose.slides.charts/ichartseries)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)