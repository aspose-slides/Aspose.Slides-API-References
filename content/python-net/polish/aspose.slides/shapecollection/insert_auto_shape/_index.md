---
title: insert_auto_shape method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów w określonym indeksie,
            stosując domyślne formatowanie szablonu.

### Zwraca

Nowo utworzony [`IAutoShape`](/slides/python-net/pl/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym ma zostać wstawiony nowy auto-kształt. |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) auto-kształtu do wstawienia. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów w określonym indeksie,
            opcjonalnie inicjalizując go domyślnym stylowaniem szablonu.

### Zwraca

Nowo utworzony [`IAutoShape`](/slides/python-net/pl/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym ma zostać wstawiony auto-kształt. |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) auto-kształtu do wstawienia. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |
| create_from_template | **bool** | True, aby zastosować domyślne stylowanie szablonu (obejmujące niepustą nazwę, prosty styl i wyśrodkowany tekst); <br/><br/> false, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na ich wartości domyślne. |



### Zobacz także
* klasa [`IAutoShape`](/slides/python-net/pl/aspose.slides/iautoshape)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* enumeracja [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)