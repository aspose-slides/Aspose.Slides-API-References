---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Создает новый кадр Summary Zoom и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Новый созданный [`ISummaryZoomFrame`](/slides/python-net/ru/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет вставлен кадр Summary Zoom. |
| x | **float** | Координата x нового кадра Summary Zoom в пунктах. |
| y | **float** | Координата y нового кадра Summary Zoom в пунктах. |
| width | **float** | Ширина нового кадра Summary Zoom в пунктах. |
| height | **float** | Высота нового кадра Summary Zoom в пунктах. |

### Примечания

Этот метод создает кадр Summary Zoom, который агрегирует ссылки-сводки для всех разделов презентации.

### Исключения

| Исключение | Описание |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception) | Выбрасывается, если презентация не содержит разделов или если целевой слайд не принадлежит ни одному разделу. |



### См. также
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* класс [`ISummaryZoomFrame`](/slides/python-net/ru/aspose.slides/isummaryzoomframe)
* класс [`PptxEditException`](/slides/python-net/ru/aspose.slides/pptxeditexception)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)