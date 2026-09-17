---
title: add_zoom_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Создает новый Zoom frame и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Новое созданное [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового Zoom frame, в пунктах. |
| y | **float** | Координата y нового Zoom frame, в пунктах. |
| width | **float** | Ширина нового Zoom frame, в пунктах. |
| height | **float** | Высота нового Zoom frame, в пунктах. |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | [`ISlide`](/slides/python-net/ru/aspose.slides/islide), на который ссылается Zoom frame;<br/><br/> должен принадлежать этой презентации. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылающийся слайд не принадлежит текущей презентации. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Создает новый Zoom frame и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Новое созданное [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового Zoom frame, в пунктах. |
| y | **float** | Координата y нового Zoom frame, в пунктах. |
| width | **float** | Ширина нового Zoom frame, в пунктах. |
| height | **float** | Высота нового Zoom frame, в пунктах. |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | [`ISlide`](/slides/python-net/ru/aspose.slides/islide), на который ссылается Zoom frame;<br/><br/> должен принадлежать этой презентации. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | Изображение для ссылающегося слайда [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage). |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылающийся слайд не принадлежит текущей презентации. |



### См. также
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* класс [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)