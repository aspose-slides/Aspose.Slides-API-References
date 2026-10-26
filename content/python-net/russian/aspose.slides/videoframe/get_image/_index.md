---
title: get_image method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/videoframe/get_image/
weight: 50
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

| Параметр | Тип | Описание |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds) | Тип границ миниатюры фигуры. |
| scale_x | **float** | Масштаб X |
| scale_y | **float** | Масштаб Y |

### См. также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* перечисление [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds)
* класс [`VideoFrame`](/slides/python-net/ru/aspose.slides/videoframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)