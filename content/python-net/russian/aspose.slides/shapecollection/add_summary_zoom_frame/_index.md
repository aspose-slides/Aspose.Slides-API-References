---
title: add_summary_zoom_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Создает новый Summary Zoom frame и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Новый созданный [`ISummaryZoomFrame`](/slides/python-net/ru/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового Summary Zoom frame в пунктах. |
| y | **float** | Координата y нового Summary Zoom frame в пунктах. |
| width | **float** | Ширина нового Summary Zoom frame в пунктах. |
| height | **float** | Высота нового Summary Zoom frame в пунктах. |

### Примечание

Этот метод создает новый Summary Zoom и помещает в него коллекцию объектов для всех секций в этой презентации.

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если в презентации нет секций или если целевой слайд не принадлежит какой-либо секции. |



### См. также
* класс [`ISummaryZoomFrame`](/slides/python-net/ru/aspose.slides/isummaryzoomframe)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)