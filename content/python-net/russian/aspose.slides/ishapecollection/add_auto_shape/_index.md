---
title: add_auto_shape method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Создает новую автоматическую форму с форматированием по умолчанию и добавляет её в конец коллекции фигур.

### Возвращает

Новая созданная [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) автоматической формы для добавления. |
| x | **float** | Координата x рамки формы в пунктах. |
| y | **float** | Координата y рамки формы в пунктах. |
| width | **float** | Ширина рамки формы в пунктах. |
| height | **float** | Высота рамки формы в пунктах. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Создает новую автоматическую форму и добавляет её в конец коллекции фигур, при необходимости инициализируя её форматированием шаблона по умолчанию.

### Возвращает

Новая созданная [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) автоматической формы для добавления. |
| x | **float** | Координата x рамки формы в пунктах. |
| y | **float** | Координата y рамки формы в пунктах. |
| width | **float** | Ширина рамки формы в пунктах. |
| height | **float** | Высота рамки формы в пунктах. |
| create_from_template | **bool** | <br/><br/>True для применения стиля шаблона по умолчанию (простой стиль, выровненный по центру текст и непустое имя) к новой форме; false для создания формы со всеми свойствами, установленными в значения по умолчанию. |



### См. также
* класс [`IAutoShape`](/slides/python-net/ru/aspose.slides/iautoshape)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)