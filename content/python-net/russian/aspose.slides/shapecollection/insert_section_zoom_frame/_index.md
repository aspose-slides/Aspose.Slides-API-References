---
title: insert_section_zoom_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Создает новый Section Zoom frame и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Новый созданный [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому вставляется Section Zoom frame. |
| x | **float** | Координата x нового Section Zoom frame, в пунктах. |
| y | **float** | Координата y нового Section Zoom frame, в пунктах. |
| width | **float** | Ширина нового Section Zoom frame, в пунктах. |
| height | **float** | Высота нового Section Zoom frame, в пунктах. |
| section | [`ISection`](/slides/python-net/ru/aspose.slides/isection) | Объект [`ISection`](/slides/python-net/ru/aspose.slides/isection), на который ссылается Section Zoom frame;<br/><br/>            должен принадлежать этой презентации и содержать хотя бы один слайд. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, если ссылка на раздел не принадлежит текущей презентации или не содержит слайдов. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Создает новый Section Zoom frame с предустановленным изображением и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Новый созданный [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому вставляется Section Zoom frame. |
| x | **float** | Координата x нового Section Zoom frame, в пунктах. |
| y | **float** | Координата y нового Section Zoom frame, в пунктах. |
| width | **float** | Ширина нового Section Zoom frame, в пунктах. |
| height | **float** | Высота нового Section Zoom frame, в пунктах. |
| section | [`ISection`](/slides/python-net/ru/aspose.slides/isection) | Объект [`ISection`](/slides/python-net/ru/aspose.slides/isection), на который ссылается Section Zoom frame;<br/><br/>            должен принадлежать этой презентации и содержать хотя бы один слайд. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | Изображение, отображаемое внутри Section Zoom frame. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, если ссылка на раздел не принадлежит текущей презентации или не содержит слайдов. |



### См. также
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`ISection`](/slides/python-net/ru/aspose.slides/isection)
* класс [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)