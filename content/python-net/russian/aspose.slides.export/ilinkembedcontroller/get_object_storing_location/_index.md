---
title: get_object_storing_location method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Определяет, где следует хранить объект.  
Этот метод вызывается один раз для каждого идентификатора объекта.  
Не гарантируется, что не будет двух объектов с одинаковыми данными, semanticName и contentType, но с разными идентификаторами.

### Возвращаемое значение

Решение



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| id | **int** | Идентификатор объекта. Этот идентификатор уникален в пределах операции сохранения. |
| entity_data | **bytes** | Двоичные данные объекта. Этот параметр может быть None, если двоичные данные объекта еще не сгенерированы. |
| semantic_name | **str** | Краткий текст, описывающий смысл объекта. Контроллер может использовать его как часть внешнего имени объекта, но обеспечение уникальности имён и их соответствия разрешённым символам лежит на диспетчере. |
| content_type | **str** | MIME-тип объекта. |
| recomended_extension | **str** | Расширение имени файла, рекомендованное для этого MIME-типа. |



### См. также
* класс [`ILinkEmbedController`](/slides/python-net/ru/aspose.slides.export/ilinkembedcontroller)
* перечисление [`LinkEmbedDecision`](/slides/python-net/ru/aspose.slides.export/linkembeddecision)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)