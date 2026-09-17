---
title: insert_zoom_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Создаёт новый Zoom-frame и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Созданный [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, в котором следует вставить Zoom-frame. |
| x | **float** | Координата x нового Zoom-frame в пунктах. |
| y | **float** | Координата y нового Zoom-frame в пунктах. |
| width | **float** | Ширина нового Zoom-frame в пунктах. |
| height | **float** | Высота нового Zoom-frame в пунктах. |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | [`ISlide`](/slides/python-net/ru/aspose.slides/islide), на который ссылается Zoom-frame. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылаемый слайд не принадлежит текущей презентации. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Создаёт новый Zoom-frame с предопределённым изображением и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Созданный [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, в котором следует вставить Zoom-frame. |
| x | **float** | Координата x нового Zoom-frame в пунктах. |
| y | **float** | Координата y нового Zoom-frame в пунктах. |
| width | **float** | Ширина нового Zoom-frame в пунктах. |
| height | **float** | Высота нового Zoom-frame в пунктах. |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | [`ISlide`](/slides/python-net/ru/aspose.slides/islide), на который ссылается Zoom-frame. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | Изображение для слайда [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage). |

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
* библиотека [`Aspose.Slides`](/slides/python-net)