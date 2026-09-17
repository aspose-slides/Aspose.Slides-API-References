---
title: add_connector method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Создает новую соединительную форму с применением стилей шаблона по умолчанию и добавляет её в конец коллекции фигур.

### Возвращаемое значение

Созданный [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector).

```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | Тип [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) соединительной формы для добавления. |
| x | **float** | Координата x рамки соединителя в пунктах. |
| y | **float** | Координата y рамки соединителя в пунктах. |
| width | **float** | Ширина рамки соединителя в пунктах. |
| height | **float** | Высота рамки соединителя в пунктах. |

## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Создает новую соединительную форму и добавляет её в конец коллекции фигур, при необходимости применяя стили шаблона по умолчанию.

### Возвращаемое значение

Созданный [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector).

```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | Тип [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) соединительной формы для создания. |
| x | **float** | Координата x рамки соединителя в пунктах. |
| y | **float** | Координата y рамки соединителя в пунктах. |
| width | **float** | Ширина рамки соединителя в пунктах. |
| height | **float** | Высота рамки соединителя в пунктах. |
| create_from_template | **bool** | True для применения стилей шаблона по умолчанию (непустое имя, простой стиль); <br/><br/> false для создания соединителя со значениями свойств по умолчанию. |

### Смотрите также
* class [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector)
* class [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)