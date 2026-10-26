---
title: insert_connector method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Создаёт новую форму-соединитель и вставляет её в коллекцию фигур в указанном индексе, применяя стили шаблона по умолчанию.

### Возвращаемое значение

Недавно созданный [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет вставлена форма-соединитель. |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | Тип [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) формы-соединителя для вставки. |
| x | **float** | Координата x рамки соединителя, в пунктах. |
| y | **float** | Координата y рамки соединителя, в пунктах. |
| width | **float** | Ширина рамки соединителя, в пунктах. |
| height | **float** | Высота рамки соединителя, в пунктах. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Создаёт новую форму-соединитель и вставляет её в коллекцию фигур в указанном индексе, опционально применяя стили шаблона по умолчанию.

### Возвращаемое значение

Недавно созданный [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет вставлена форма-соединитель. |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | Тип [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) формы-соединителя для вставки. |
| x | **float** | Координата x рамки соединителя, в пунктах. |
| y | **float** | Координата y рамки соединителя, в пунктах. |
| width | **float** | Ширина рамки соединителя, в пунктах. |
| height | **float** | Высота рамки соединителя, в пунктах. |
| create_from_template | **bool** | True — применить стили шаблона по умолчанию (непустое имя, простой стиль);<br/><br/>false — создать соединитель со значениями свойств по умолчанию. |



### См. также
* class [`IConnector`](/slides/python-net/ru/aspose.slides/iconnector)
* class [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)