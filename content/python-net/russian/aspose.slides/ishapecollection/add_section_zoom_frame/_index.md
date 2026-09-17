---
title: add_section_zoom_frame method
second_title: Aspose.Slides для Python через .NET — справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Создаёт новый кадр Section Zoom и добавляет его в конец коллекции фигур.

### Returns

Новое созданное [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | Координата x нового кадра Section Zoom, в пунктах. |
| y | **float** | Координата y нового кадра Section Zoom, в пунктах. |
| width | **float** | Ширина нового кадра Section Zoom, в пунктах. |
| height | **float** | Высота нового кадра Section Zoom, в пунктах. |
| section | [`ISection`](/slides/python-net/ru/aspose.slides/isection) | [`ISection`](/slides/python-net/ru/aspose.slides/isection) , на который ссылается кадр Section Zoom; <br/><br/>            должен принадлежать этой презентации и содержать хотя бы один слайд. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылка на раздел не принадлежит текущей презентации или не содержит слайдов. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Создаёт новый кадр Section Zoom с предопределённым изображением и добавляет его в конец
            коллекции фигур.

### Returns

Новое созданное [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | Координата x нового кадра Section Zoom, в пунктах. |
| y | **float** | Координата y нового кадра Section Zoom, в пунктах. |
| width | **float** | Ширина нового кадра Section Zoom, в пунктах. |
| height | **float** | Высота нового кадра Section Zoom, в пунктах. |
| section | [`ISection`](/slides/python-net/ru/aspose.slides/isection) | [`ISection`](/slides/python-net/ru/aspose.slides/isection) , на который ссылается кадр Section Zoom; <br/><br/>            должен принадлежать этой презентации и содержать хотя бы один слайд. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) для отображения внутри кадра Section Zoom. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если ссылка на раздел не принадлежит текущей презентации или не содержит слайдов. |



### See Also
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`ISection`](/slides/python-net/ru/aspose.slides/isection)
* класс [`ISectionZoomFrame`](/slides/python-net/ru/aspose.slides/isectionzoomframe)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)