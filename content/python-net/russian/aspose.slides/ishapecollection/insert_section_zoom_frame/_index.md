---
title: insert_section_zoom_frame method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Создаёт новый кадр Section Zoom и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Недавно созданный [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет вставлен кадр Section Zoom. |
| x | **float** | Координата x нового кадра Section Zoom в пунктах. |
| y | **float** | Координата y нового кадра Section Zoom в пунктах. |
| width | **float** | Ширина нового кадра Section Zoom в пунктах. |
| height | **float** | Высота нового кадра Section Zoom в пунктах. |
| section | [`ISection`](/slides/python-net/ru/aspose.slides/isection) | Объект [`ISection`](/slides/python-net/ru/aspose.slides/isection), на который ссылается кадр Section Zoom;<br/><br/>            должен принадлежать данной презентации и содержать как минимум один слайд. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылка на раздел не принадлежит текущей презентации или не содержит слайдов. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Создаёт новый кадр Section Zoom с предустановленным изображением и вставляет его в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Недавно созданный [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет вставлен кадр Section Zoom. |
| x | **float** | Координата x нового кадра Section Zoom в пунктах. |
| y | **float** | Координата y нового кадра Section Zoom в пунктах. |
| width | **float** | Ширина нового кадра Section Zoom в пунктах. |
| height | **float** | Высота нового кадра Section Zoom в пунктах. |
| section | [`ISection`](/slides/python-net/ru/aspose.slides/isection) | Объект [`ISection`](/slides/python-net/ru/aspose.slides/isection), на который ссылается кадр Section Zoom;<br/><br/>            должен принадлежать данной презентации и содержать как минимум один слайд. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | Изображение, отображаемое внутри кадра Section Zoom. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылка на раздел не принадлежит текущей презентации или не содержит слайдов. |



### См. также
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`ISection`](/slides/python-net/ru/aspose.slides/isection)
* класс [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)