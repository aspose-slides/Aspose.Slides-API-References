---
title: get_tile method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/ipatternformat/get_tile/
weight: 10
---
## get_tile(self, style_color) {#asposepydrawingcolor}
Создаёт изображение плитки для заливки шаблоном.

### Возвращает

Плитка **aspose.slides.Bitmap**.



```python
def get_tile(self, style_color):
    ...
```



| Parameter | Type | Description |
| :- | :- | :- |
| style_color | **aspose.slides.Color** | Объект **aspose.slides.Color** по умолчанию, <br/><br/> определённый в объекте StyleEx класса ShapeEx. Цвета заливки могут зависеть от него. |


## get_tile(self, background, foreground) {#asposepydrawingcolor-asposepydrawingcolor}
Создаёт изображение плитки для заливки шаблоном с указанными цветами.

### Возвращает

Плитка **aspose.slides.Bitmap**.



```python
def get_tile(self, background, foreground):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| background | **aspose.slides.Color** | Фоновый **aspose.slides.Color** для шаблона. |
| foreground | **aspose.slides.Color** | Цвет переднего плана **aspose.slides.Color** для шаблона. |



### См. также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`IPatternFormat`](/slides/python-net/ru/aspose.slides/ipatternformat)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)