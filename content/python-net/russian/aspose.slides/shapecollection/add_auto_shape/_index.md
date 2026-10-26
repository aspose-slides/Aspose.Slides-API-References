---
title: add_auto_shape method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Создает новую автофигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур.

### Возвращаемое значение

Недавно созданный [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) автофигуры, которую необходимо добавить. |
| x | **float** | Координата x рамки фигуры, в пунктах. |
| y | **float** | Координата y рамки фигуры, в пунктах. |
| width | **float** | Ширина рамки фигуры, в пунктах. |
| height | **float** | Высота рамки фигуры, в пунктах. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Создает новую автофигуру и добавляет её в конец коллекции фигур, при желании инициализируя её форматированием шаблона по умолчанию.

### Возвращаемое значение

Недавно созданный [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) автофигуры, которую необходимо добавить. |
| x | **float** | Координата x рамки фигуры, в пунктах. |
| y | **float** | Координата y рамки фигуры, в пунктах. |
| width | **float** | Ширина рамки фигуры, в пунктах. |
| height | **float** | Высота рамки фигуры, в пунктах. |
| create_from_template | **bool** | True, если применить стилевое оформление шаблона по умолчанию (простой стиль, центрированный текст и непустое имя)<br/><br/>            к новой фигуре; false, чтобы создать фигуру со всеми свойствами, установленными в их значения по умолчанию. |



### См. также
* класс [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* перечисление [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)