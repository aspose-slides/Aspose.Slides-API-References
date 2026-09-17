---
title: add_video_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_video_frame/
weight: 160
---
## add_video_frame(self, x, y, width, height, fname) {#float-float-float-float-str}
Создает новый видеокадр и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Созданный [`IVideoFrame`](/slides/python-net/ru/aspose.slides/ivideoframe).



```python
def add_video_frame(self, x, y, width, height, fname):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового видеокадра, в пунктах. |
| y | **float** | Координата y нового видеокадра, в пунктах. |
| width | **float** | Ширина нового видеокадра, в пунктах. |
| height | **float** | Высота нового видеокадра, в пунктах. |
| fname | **str** | Путь или имя видеофайла для встраивания. |


## add_video_frame(self, x, y, width, height, video) {#float-float-float-float-ivideo}
Создает новый видеокадр и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Созданный [`IVideoFrame`](/slides/python-net/ru/aspose.slides/ivideoframe).



```python
def add_video_frame(self, x, y, width, height, video):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового видеокадра, в пунктах. |
| y | **float** | Координата y нового видеокадра, в пунктах. |
| width | **float** | Ширина нового видеокадра, в пунктах. |
| height | **float** | Высота нового видеокадра, в пунктах. |
| video | [`IVideo`](/slides/python-net/ru/aspose.slides/ivideo) | Объект [`IVideo`](/slides/python-net/ru/aspose.slides/ivideo) для встраивания в видеокадр. |



### См. также
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* класс [`IVideo`](/slides/python-net/ru/aspose.slides/ivideo)
* класс [`IVideoFrame`](/slides/python-net/ru/aspose.slides/ivideoframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)