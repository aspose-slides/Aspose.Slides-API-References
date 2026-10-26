---
title: insert_ole_object_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Создаёт новый фрейм OLE-объекта и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Созданный [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe).

```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому следует вставить фрейм OLE-объекта. |
| x | **float** | Координата x нового фрейма OLE, в пунктах. |
| y | **float** | Координата y нового фрейма OLE, в пунктах. |
| width | **float** | Ширина нового фрейма OLE, в пунктах. |
| height | **float** | Высота нового фрейма OLE, в пунктах. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo) | Информация о встроенных данных OLE ([`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo)). |

## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Создаёт новый фрейм OLE-объекта и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Созданный фрейм OLE-объекта.

```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому следует вставить фрейм OLE-объекта. |
| x | **float** | Координата x нового фрейма OLE, в пунктах. |
| y | **float** | Координата y нового фрейма OLE, в пунктах. |
| width | **float** | Ширина нового фрейма OLE, в пунктах. |
| height | **float** | Высота нового фрейма OLE, в пунктах. |
| class_name | **str** | Имя класса OLE-объекта. |
| path | **str** | Путь к связанному файлу. <br/><br/>Этот путь сохраняется дословно в презентации.<br/><br/>Если указан относительный путь, файл будет недоступен при открытии<br/><br/>презентации из другого каталога. |

### См. также
* класс [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo)
* класс [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)