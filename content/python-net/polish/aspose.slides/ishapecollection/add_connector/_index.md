---
title: add_connector method
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Tworzy nowy kształt łącznika z domyślnym stylem szablonu i dodaje go na koniec kolekcji kształtów.

### Zwraca

Nowo utworzony [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector).

```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) kształtu łącznika do dodania. |
| x | **float** | Współrzędna x ramki łącznika, w punktach. |
| y | **float** | Współrzędna y ramki łącznika, w punktach. |
| width | **float** | Szerokość ramki łącznika, w punktach. |
| height | **float** | Wysokość ramki łącznika, w punktach. |

## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Tworzy nowy kształt łącznika i dodaje go na koniec kolekcji kształtów, opcjonalnie stosując domyślny styl szablonu.

### Zwraca

Nowo utworzony [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector).

```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) kształtu łącznika do utworzenia. |
| x | **float** | Współrzędna x ramki łącznika, w punktach. |
| y | **float** | Współrzędna y ramki łącznika, w punktach. |
| width | **float** | Szerokość ramki łącznika, w punktach. |
| height | **float** | Wysokość ramki łącznika, w punktach. |
| create_from_template | **bool** | True, aby zastosować domyślny styl szablonu (niepusta nazwa, prosty styl); <br/><br/>false, aby utworzyć łącznik z domyślnymi wartościami właściwości. |

### Zobacz także
* klasa [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* wyliczenie [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)