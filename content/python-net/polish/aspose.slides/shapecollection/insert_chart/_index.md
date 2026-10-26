---
title: insert_chart method
second_title: Aspose.Slides dla Pythona via .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Tworzy nowy wykres, inicjalizuje go danymi przykładowymi serii i ustawieniami oraz wstawia go do kolekcji kształtów pod określonym indeksem.

### Zwraca

Nowo utworzony [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ wykresu do utworzenia. |
| x | **float** | Współrzędna x nowego wykresu, w punktach. |
| y | **float** | Współrzędna y nowego wykresu, w punktach. |
| width | **float** | Szerokość nowego wykresu, w punktach. |
| height | **float** | Wysokość nowego wykresu, w punktach. |
| index | **int** | Indeks zerowy, pod którym wstawić nowy wykres w kolekcji kształtów. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Tworzy nowy wykres, inicjalizuje go danymi przykładowymi serii i ustawieniami oraz wstawia go do kolekcji kształtów pod określonym indeksem.

### Zwraca

Nowo utworzony [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ wykresu do utworzenia. |
| x | **float** | Współrzędna x nowego wykresu, w punktach. |
| y | **float** | Współrzędna y nowego wykresu, w punktach. |
| width | **float** | Szerokość nowego wykresu, w punktach. |
| height | **float** | Wysokość nowego wykresu, w punktach. |
| index | **int** | Indeks zerowy, pod którym wstawić nowy wykres w kolekcji kształtów. |
| init_with_sample | **bool** | True, aby zainicjalizować nowy wykres danymi przykładowymi serii i ustawieniami; <br/><br/>false, aby utworzyć wykres bez serii i jedynie z minimalnymi ustawieniami, co przyspiesza tworzenie. |



### Zobacz także
* wyliczenie [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype)
* klasa [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)