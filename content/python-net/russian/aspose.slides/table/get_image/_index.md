---
title: get_image method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/table/get_image/
weight: 30
---
## get_image(self) {#}
Возвращает миниатюру Shape.  
ShapeThumbnailBounds.Shape тип границ миниатюры Shape используется по умолчанию.

### Возвращаемое значение

миниатюра Shape.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Возвращает миниатюру Shape.

### Возвращаемое значение

Миниатюра Shape или None в случае, когда используется ShapeThumbnailBounds.Appearance и у Shape нет видимых элементов.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds) | Тип границ миниатюры Shape. |
| scale_x | **float** | масштаб X |
| scale_y | **float** | масштаб Y |



### См. также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* перечисление [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds)
* класс [`Table`](/slides/python-net/ru/aspose.slides/table)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)