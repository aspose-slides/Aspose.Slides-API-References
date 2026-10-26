---
title: insert_ole_object_frame method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Создает новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Новосозданный [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому вставляется OLE-объектный кадр. |
| x | **float** | Координата x нового OLE-кадра в точках. |
| y | **float** | Координата y нового OLE-кадра в точках. |
| width | **float** | Ширина нового OLE-кадра в точках. |
| height | **float** | Высота нового OLE-кадра в точках. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo) | Информация о встроенных данных OLE ([`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Создает новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Новосозданный [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому вставляется OLE-объектный кадр. |
| x | **float** | Координата x нового OLE-кадра в точках. |
| y | **float** | Координата y нового OLE-кадра в точках. |
| width | **float** | Ширина нового OLE-кадра в точках. |
| height | **float** | Высота нового OLE-кадра в точках. |
| class_name | **str** | Имя класса OLE-объекта. |
| path | **str** | Путь к связанному файлу. <br/><br/>Этот путь сохраняется без изменений в презентации.<br/><br/>            Если указан относительный путь, файл будет недоступен при открытии<br/><br/>            презентации из другого каталога. |



### См. также
* класс [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo)
* класс [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)