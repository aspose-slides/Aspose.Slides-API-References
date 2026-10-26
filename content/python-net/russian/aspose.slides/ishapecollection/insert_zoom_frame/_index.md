---
title: insert_zoom_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Создаёт новый Zoom-кадр и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Новый созданный [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой-базовый индекс, в котором вставляется Zoom-кадр. |
| x | **float** | Координата x нового Zoom-кадра в пунктах. |
| y | **float** | Координата y нового Zoom-кадра в пунктах. |
| width | **float** | Ширина нового Zoom-кадра в пунктах. |
| height | **float** | Высота нового Zoom-кадра в пунктах. |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | [`ISlide`](/slides/python-net/ru/aspose.slides/islide), на который ссылается Zoom-кадр. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылка на слайд не принадлежит текущей презентации. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Создаёт новый Zoom-кадр с предустановленным изображением и вставляет его в коллекцию фигур
            по указанному индексу.

### Возвращаемое значение

Новый созданный [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой-базовый индекс, в котором вставляется Zoom-кадр. |
| x | **float** | Координата x нового Zoom-кадра в пунктах. |
| y | **float** | Координата y нового Zoom-кадра в пунктах. |
| width | **float** | Ширина нового Zoom-кадра в пунктах. |
| height | **float** | Высота нового Zoom-кадра в пунктах. |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | [`ISlide`](/slides/python-net/ru/aspose.slides/islide), на который ссылается Zoom-кадр. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | Изображение для ссылающегося слайда [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage). |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылка на слайд не принадлежит текущей презентации. |



### См. также
* class [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* class [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* class [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* class [`IZoomFrame`](/slides/python-net/ru/aspose.slides/izoomframe)
* module [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)