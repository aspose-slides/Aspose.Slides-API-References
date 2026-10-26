---
title: add_zoom_frame method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Создает новый Zoom-кадр и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Созданный [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового Zoom-кадра, в пунктах. |
| y | **float** | Координата y нового Zoom-кадра, в пунктах. |
| width | **float** | Ширина нового Zoom-кадра, в пунктах. |
| height | **float** | Высота нового Zoom-кадра, в пунктах. |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Экземпляр [`ISlide`](/slides/python-net/ru/aspose.slides/islide), на который ссылается Zoom-кадр;<br/><br/>            должен принадлежать этой презентации. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылаемый слайд не принадлежит текущей презентации. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Создает новый Zoom-кадр и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Созданный [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового Zoom-кадра, в пунктах. |
| y | **float** | Координата y нового Zoom-кадра, в пунктах. |
| width | **float** | Ширина нового Zoom-кадра, в пунктах. |
| height | **float** | Высота нового Zoom-кадра, в пунктах. |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Экземпляр [`ISlide`](/slides/python-net/ru/aspose.slides/islide), на который ссылается Zoom-кадр;<br/><br/>            должен принадлежать этой презентации. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | Изображение для ссылающегося слайда [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage). |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылаемый слайд не принадлежит текущей презентации. |



### См. также
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* класс [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)