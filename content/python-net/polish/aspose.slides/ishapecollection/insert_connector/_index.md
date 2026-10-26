---
title: insert_connector method
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów w określonym indeksie,
            stosując domyślne formatowanie szablonu.

### Returns

Nowo utworzony [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Zero-based indeks, w którym ma zostać wstawiony kształt łącznika. |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) kształtu łącznika, który ma zostać wstawiony. |
| x | **float** | Współrzędna x ramki łącznika, w punktach. |
| y | **float** | Współrzędna y ramki łącznika, w punktach. |
| width | **float** | Szerokość ramki łącznika, w punktach. |
| height | **float** | Wysokość ramki łącznika, w punktach. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów w określonym indeksie,
            opcjonalnie stosując domyślne formatowanie szablonu.

### Returns

Nowo utworzony [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Zero-based indeks, w którym ma zostać wstawiony kształt łącznika. |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) kształtu łącznika, który ma zostać wstawiony. |
| x | **float** | Współrzędna x ramki łącznika, w punktach. |
| y | **float** | Współrzędna y ramki łącznika, w punktach. |
| width | **float** | Szerokość ramki łącznika, w punktach. |
| height | **float** | Wysokość ramki łącznika, w punktach. |
| create_from_template | **bool** | True, aby zastosować domyślne formatowanie szablonu (niepusta nazwa, prosty styl);<br/><br/>            false, aby utworzyć łącznik z domyślnymi wartościami właściwości. |



### See Also
* klasa [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* enumeracja [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)