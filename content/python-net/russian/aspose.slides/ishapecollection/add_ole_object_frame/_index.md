---
title: add_ole_object_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Создаёт новый OLE-кадр объекта и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Созданный [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового OLE-кадра в пунктах. |
| y | **float** | Координата y нового OLE-кадра в пунктах. |
| width | **float** | Ширина нового OLE-кадра в пунктах. |
| height | **float** | Высота нового OLE-кадра в пунктах. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo) | Информация о вложенных данных OLE ([`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Создаёт новый OLE-кадр объекта и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Созданный [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового OLE-кадра в пунктах. |
| y | **float** | Координата y нового OLE-кадра в пунктах. |
| width | **float** | Ширина нового OLE-кадра в пунктах. |
| height | **float** | Высота нового OLE-кадра в пунктах. |
| class_name | **str** | Имя класса объекта OLE. |
| path | **str** | Путь к связанному файлу. <br/><br/>Этот путь сохраняется дословно в презентации.<br/><br/>            Если указан относительный путь, файл будет недоступен при открытии<br/><br/>            презентации из другого каталога. |



### См. также
* класс [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo)
* класс [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)