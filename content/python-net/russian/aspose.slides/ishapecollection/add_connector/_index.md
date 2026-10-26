---
title: add_connector method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Создает новую соединительную форму с применением стилей шаблона по умолчанию и добавляет её в конец коллекции форм.

### Возвращаемое значение

Новосозданный [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | Тип [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) соединительной формы для добавления. |
| x | **float** | Координата x рамки соединителя, в пунктах. |
| y | **float** | Координата y рамки соединителя, в пунктах. |
| width | **float** | Ширина рамки соединителя, в пунктах. |
| height | **float** | Высота рамки соединителя, в пунктах. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Создает новую соединительную форму и добавляет её в конец коллекции форм, при желании применяя стили шаблона по умолчанию.

### Возвращаемое значение

Новосозданный [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | Тип [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) соединительной формы для создания. |
| x | **float** | Координата x рамки соединителя, в пунктах. |
| y | **float** | Координата y рамки соединителя, в пунктах. |
| width | **float** | Ширина рамки соединителя, в пунктах. |
| height | **float** | Высота рамки соединителя, в пунктах. |
| create_from_template | **bool** | True, чтобы применить стили шаблона по умолчанию (ненулевое имя, простой стиль); <br/><br/>            false, чтобы создать соединитель со значениями свойств по умолчанию. |



### См. также
* класс [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* перечисление [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)