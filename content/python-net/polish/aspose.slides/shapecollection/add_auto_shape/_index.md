---
title: add_auto_shape method
second_title: Aspose.Slides dla Pythona przy użyciu .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Tworzy nowy auto shape z domyślnym formatowaniem i dodaje go na koniec kolekcji kształtów.

### Zwraca

Nowo utworzony [`IAutoShape`](/slides/python-net/pl/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | Typ [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) auto shape do dodania. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Tworzy nowy auto shape i dodaje go na koniec kolekcji kształtów, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu.

### Zwraca

Nowo utworzony [`IAutoShape`](/slides/python-net/pl/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | Typ [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) auto shape do dodania. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |
| create_from_template | **bool** | True, aby zastosować domyślne formatowanie szablonu (prosty styl, wyśrodkowany tekst i niepustą nazwę) do nowego kształtu; false, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na ich domyślne wartości. |



### Zobacz także
* klasa [`IAutoShape`](/slides/python-net/pl/aspose.slides/iautoshape)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* wyliczenie [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)