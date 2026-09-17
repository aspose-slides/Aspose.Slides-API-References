---
title: get_image method
second_title: Aspose.Slides for Python via .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/shape/get_image/
weight: 30
---
## get_image(self) {#}
Возвращает миниатюру формы.
ShapeThumbnailBounds.Shape тип границ миниатюры Shape используется по умолчанию.

### Возвращаемое значение

Миниатюра формы.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Возвращает миниатюру формы.

### Возвращаемое значение

Миниатюра формы или None в случае, когда используется ShapeThumbnailBounds.Appearance и у формы нет видимых элементов.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds) | Тип границ миниатюры Shape. |
| scale_x | **float** | масштаб X |
| scale_y | **float** | масштаб Y |



### Смотрите также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* перечисление [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)