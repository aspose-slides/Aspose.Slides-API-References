---
title: add_summary_zoom_frame method
second_title: Aspose.Slides для Python через .NET API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Создаёт новый Summary Zoom frame и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Новосозданный [`ISummaryZoomFrame`](/slides/python-net/ru/aspose.slides/isummaryzoomframe).

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового Summary Zoom frame, в пунктах. |
| y | **float** | Координата y нового Summary Zoom frame, в пунктах. |
| width | **float** | Ширина нового Summary Zoom frame, в пунктах. |
| height | **float** | Высота нового Summary Zoom frame, в пунктах. |

### Примечания

Этот метод создает Summary Zoom frame, который агрегирует ссылки-сводки для всех разделов в презентации.

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если в презентации нет разделов или если целевой слайд не принадлежит ни к одному разделу. |

### См. также
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* класс [`ISummaryZoomFrame`](/slides/python-net/ru/aspose.slides/isummaryzoomframe)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)