---
title: insert_auto_shape method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Создаёт новую автофигуру и вставляет её в коллекцию фигур в указанном индексе, применяя форматирование шаблона по умолчанию.

### Возвращаемое значение

Новосозданный [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс, начиная с нуля, по которому будет вставлена новая автофигура. |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) автофигуры, которую необходимо вставить. |
| x | **float** | Координата x рамки фигуры в пунктах. |
| y | **float** | Координата y рамки фигуры в пунктах. |
| width | **float** | Ширина рамки фигуры в пунктах. |
| height | **float** | Высота рамки фигуры в пунктах. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Создаёт новую автофигуру и вставляет её в коллекцию фигур в указанном индексе, при желании инициализируя её стилем шаблона по умолчанию.

### Возвращаемое значение

Новосозданный [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс, начиная с нуля, по которому будет вставлена автофигура. |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) автофигуры, которую необходимо вставить. |
| x | **float** | Координата x рамки фигуры в пунктах. |
| y | **float** | Координата y рамки фигуры в пунктах. |
| width | **float** | Ширина рамки фигуры в пунктах. |
| height | **float** | Высота рамки фигуры в пунктах. |
| create_from_template | **bool** | True для применения стандартного оформления шаблона (включая непустое имя, простой стиль и центрированный текст); <br/><br/>false для создания фигуры со всеми свойствами, установленными в их значения по умолчанию. |



### См. также
* класс [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* перечисление [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)