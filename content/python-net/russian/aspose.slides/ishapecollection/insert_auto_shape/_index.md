---
title: insert_auto_shape method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Создает новую автофигуру и вставляет её в коллекцию фигур по указанному индексу, применяя форматирование шаблона по умолчанию.

### Возвращаемое значение

Созданный [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому вставляется новая автофигура. |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) автофигуры, которую нужно вставить. |
| x | **float** | Координата x рамки фигуры в пунктах. |
| y | **float** | Координата y рамки фигуры в пунктах. |
| width | **float** | Ширина рамки фигуры в пунктах. |
| height | **float** | Высота рамки фигуры в пунктах. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Создает новую автофигуру и вставляет её в коллекцию фигур по указанному индексу, при необходимости инициализируя её стилем шаблона по умолчанию.

### Возвращаемое значение

Созданный [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому вставляется автофигура. |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) автофигуры, которую нужно вставить. |
| x | **float** | Координата x рамки фигуры в пунктах. |
| y | **float** | Координата y рамки фигуры в пунктах. |
| width | **float** | Ширина рамки фигуры в пунктах. |
| height | **float** | Высота рамки фигуры в пунктах. |
| create_from_template | **bool** | True для применения стилей шаблона по умолчанию (включая непустое имя, простой стиль и центрированный текст); <br/><br/> false для создания фигуры со всеми свойствами, установленными по умолчанию. |



### См. также
* класс [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* перечисление [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)