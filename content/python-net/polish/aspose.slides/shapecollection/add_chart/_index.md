---
title: add_chart method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów.

### Zwraca

Nowo utworzony [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ wykresu do dodania. |
| x | **float** | Współrzędna x nowego wykresu, w punktach. |
| y | **float** | Współrzędna y nowego wykresu, w punktach. |
| width | **float** | Szerokość wykresu, w punktach. |
| height | **float** | Wysokość wykresu, w punktach. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów.

### Zwraca

Nowo utworzony [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype) | Typ wykresu do dodania. |
| x | **float** | Współrzędna x nowego wykresu, w punktach. |
| y | **float** | Współrzędna y nowego wykresu, w punktach. |
| width | **float** | Szerokość wykresu, w punktach. |
| height | **float** | Wysokość wykresu, w punktach. |
| init_with_sample | **bool** | True aby zainicjować nowy wykres przykładowymi danymi serii i ustawieniami; <br/><br/>false aby utworzyć wykres bez serii i z minimalnymi ustawieniami, co przyspiesza tworzenie. |



### Zobacz również
* enumeracja [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype)
* klasa [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)