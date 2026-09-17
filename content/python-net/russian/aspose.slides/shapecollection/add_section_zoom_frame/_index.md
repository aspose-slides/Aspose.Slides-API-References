---
title: add_section_zoom_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Создает новый кадр Section Zoom и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Созданный [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового кадра Section Zoom в пунктах. |
| y | **float** | Координата y нового кадра Section Zoom в пунктах. |
| width | **float** | Ширина нового кадра Section Zoom в пунктах. |
| height | **float** | Высота нового кадра Section Zoom в пунктах. |
| section | [`ISection`](/slides/python-net/ru/aspose.slides/isection) | [`ISection`](/slides/python-net/ru/aspose.slides/isection) ссылка на кадр Section Zoom; должен принадлежать данной презентации и содержать хотя бы один слайд. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылка на раздел не принадлежит текущей презентации или не содержит слайды. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Создает новый кадр Section Zoom с предопределенным изображением и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Созданный [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового кадра Section Zoom в пунктах. |
| y | **float** | Координата y нового кадра Section Zoom в пунктах. |
| width | **float** | Ширина нового кадра Section Zoom в пунктах. |
| height | **float** | Высота нового кадра Section Zoom в пунктах. |
| section | [`ISection`](/slides/python-net/ru/aspose.slides/isection) | [`ISection`](/slides/python-net/ru/aspose.slides/isection) ссылка на кадр Section Zoom; должен принадлежать данной презентации и содержать хотя бы один слайд. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) для отображения внутри кадра Section Zoom. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылка на раздел не принадлежит текущей презентации или не содержит слайды. |



### См. также
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`ISection`](/slides/python-net/ru/aspose.slides/isection)
* класс [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)