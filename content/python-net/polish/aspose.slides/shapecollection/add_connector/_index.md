---
title: add_connector method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Tworzy nowy kształt łącza z domyślnym formatowaniem szablonu i dodaje go na koniec kolekcji kształtów.

### Zwraca

Nowo utworzony [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) kształtu łącza do dodania. |
| x | **float** | Współrzędna x ramki łącza, w punktach. |
| y | **float** | Współrzędna y ramki łącza, w punktach. |
| width | **float** | Szerokość ramki łącza, w punktach. |
| height | **float** | Wysokość ramki łącza, w punktach. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Tworzy nowy kształt łącza i dodaje go na koniec kolekcji kształtów,
            opcjonalnie stosując domyślne formatowanie szablonu.

### Zwraca

Nowo utworzony [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) kształtu łącza do utworzenia. |
| x | **float** | Współrzędna x ramki łącza, w punktach. |
| y | **float** | Współrzędna y ramki łącza, w punktach. |
| width | **float** | Szerokość ramki łącza, w punktach. |
| height | **float** | Wysokość ramki łącza, w punktach. |
| create_from_template | **bool** | True aby zastosować domyślne formatowanie szablonu (niepusta nazwa, prosty styl); <br/><br/>            false aby utworzyć łącze z domyślnymi wartościami właściwości. |



### Patrz także
* class [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector)
* class [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)