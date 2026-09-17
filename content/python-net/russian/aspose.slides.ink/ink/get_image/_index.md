---
title: get_image method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
Возвращает миниатюру фигуры.
            Тип границ миниатюры фигуры ShapeThumbnailBounds.Shape используется по умолчанию.

### Возвращаемое значение

Миниатюра фигуры.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Возвращает миниатюру фигуры.

### Возвращаемое значение

Миниатюра фигуры или None в случае, когда используется ShapeThumbnailBounds.Appearance и у фигуры нет видимых элементов.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds) | Тип границ миниатюры фигуры. |
| scale_x | **float** | масштаб X |
| scale_y | **float** | масштаб Y |



### См. также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`Ink`](/slides/python-net/ru/aspose.slides.ink/ink)
* перечисление [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds)
* модуль [`aspose.slides.ink`](/slides/python-net/ru/aspose.slides.ink)
* библиотека [`Aspose.Slides`](/slides/python-net)