---
title: insert_connector method
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Tworzy nowy kształt połączenia i wstawia go do kolekcji kształtów w określonym indeksie, stosując domyślne stylowanie szablonu.

### Zwraca

Nowo utworzony [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the connector shape. |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) of the connector shape to insert. |
| x | **float** | The x-coordinate of the connector’s frame, in points. |
| y | **float** | The y-coordinate of the connector’s frame, in points. |
| width | **float** | The width of the connector’s frame, in points. |
| height | **float** | The height of the connector’s frame, in points. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Tworzy nowy kształt połączenia i wstawia go do kolekcji kształtów w określonym indeksie, opcjonalnie stosując domyślne stylowanie szablonu.

### Zwraca

Nowo utworzony [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the connector shape. |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) of the connector shape to insert. |
| x | **float** | The x-coordinate of the connector’s frame, in points. |
| y | **float** | The y-coordinate of the connector’s frame, in points. |
| width | **float** | The width of the connector’s frame, in points. |
| height | **float** | The height of the connector’s frame, in points. |
| create_from_template | **bool** | True, aby zastosować domyślne stylowanie szablonu (niepusta nazwa, prosty styl);<br/><br/>            false, aby utworzyć połączenie z domyślnymi wartościami właściwości. |



### Zobacz także
* klasa [`IConnector`](/slides/python-net/pl/aspose.slides/iconnector)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* enumeracja [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)