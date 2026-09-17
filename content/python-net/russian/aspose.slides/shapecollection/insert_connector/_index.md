---
title: insert_connector method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Создает новую соединительную фигуру и вставляет её в коллекцию фигур по указанному индексу, применяя стиль шаблона по умолчанию.

### Возвращаемое значение

Новое созданное [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет вставлена соединительная фигура. |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) соединительной фигуры, которую нужно вставить. |
| x | **float** | Координата x рамки соединительной фигуры, в пунктах. |
| y | **float** | Координата y рамки соединительной фигуры, в пунктах. |
| width | **float** | Ширина рамки соединительной фигуры, в пунктах. |
| height | **float** | Высота рамки соединительной фигуры, в пунктах. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Создает новую соединительную фигуру и вставляет её в коллекцию фигур по указанному индексу, при необходимости применяя стиль шаблона по умолчанию.

### Возвращаемое значение

Новое созданное [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет вставлена соединительная фигура. |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) соединительной фигуры, которую нужно вставить. |
| x | **float** | Координата x рамки соединительной фигуры, в пунктах. |
| y | **float** | Координата y рамки соединительной фигуры, в пунктах. |
| width | **float** | Ширина рамки соединительной фигуры, в пунктах. |
| height | **float** | Высота рамки соединительной фигуры, в пунктах. |
| create_from_template | **bool** | True, чтобы применить стиль шаблона по умолчанию (непустое имя, простой стиль);<br/><br/>false, чтобы создать соединительную фигуру со значениями свойств по умолчанию. |



### См. также
* класс [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* перечисление [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)