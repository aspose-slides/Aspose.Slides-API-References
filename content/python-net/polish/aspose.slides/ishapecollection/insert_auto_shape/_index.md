---
title: insert_auto_shape method
second_title: Aspose.Slides dla Pythona via .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Tworzy nowy auto shape i wstawia go do kolekcji kształtów pod podanym indeksem, stosując domyślne formatowanie szablonu.

### Zwraca

Nowo utworzony [`IAutoShape`](/slides/python-net/pl/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, pod którym wstawić nowy auto shape. |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) automatycznego kształtu do wstawienia. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Tworzy nowy auto shape i wstawia go do kolekcji kształtów pod podanym indeksem, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu.

### Zwraca

Nowo utworzony [`IAutoShape`](/slides/python-net/pl/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, pod którym wstawić auto shape. |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) automatycznego kształtu do wstawienia. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |
| create_from_template | **bool** | True, aby zastosować domyślne formatowanie szablonu (w tym niepustą nazwę, prosty styl i wyśrodkowany tekst); false, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na ich domyślne wartości. |



### Zobacz także
* klasa [`IAutoShape`](/slides/python-net/pl/aspose.slides/iautoshape)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* enumeracja [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)