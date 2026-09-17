---
title: get_image method
second_title: Aspose.Slides для Python через .NET — справочник API
description: 
type: docs
url: /ru/aspose.slides/graphicalobject/get_image/
weight: 30
---
## get_image(self) {#}
Возвращает Shape thumbnail.  
Тип границ ShapeThumbnailBounds.Shape используется по умолчанию.

### Возвращаемое значение

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Возвращает Shape thumbnail.

### Возвращаемое значение

Shape thumbnail или None в случае, если используется ShapeThumbnailBounds.Appearance и у фигуры нет видимых элементов.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds) | Тип границ Shape thumbnail. |
| scale_x | **float** | масштаб X |
| scale_y | **float** | масштаб Y |



### См. также
* class [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject)
* class [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)