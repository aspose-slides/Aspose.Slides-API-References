---
title: add_ole_object_frame method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Создает новый кадр OLE-объекта и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Недавно созданный [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new OLE frame, in points. |
| y | **float** | The y-coordinate of the new OLE frame, in points. |
| width | **float** | The width of the new OLE frame, in points. |
| height | **float** | The height of the new OLE frame, in points. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo) | The information about the embedded OLE data ([`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Создает новый кадр OLE-объекта и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Недавно созданный [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new OLE frame, in points. |
| y | **float** | The y-coordinate of the new OLE frame, in points. |
| width | **float** | The width of the new OLE frame, in points. |
| height | **float** | The height of the new OLE frame, in points. |
| class_name | **str** | The class name of the OLE object. |
| path | **str** | Путь к связанному файлу. <br/><br/>Этот путь сохраняется дословно в презентации.<br/><br/>            Если указан относительный путь, файл будет недоступен при открытии<br/><br/>            презентации из другого каталога. |



### См. также
* класс [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo)
* класс [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)