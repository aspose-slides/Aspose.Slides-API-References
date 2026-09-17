---
title: get_image method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
Возвращает миниатюру формы.
            Тип границ миниатюры формы ShapeThumbnailBounds.Shape используется по умолчанию.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds) | Тип границ миниатюры формы. |
| scale_x | **float** | масштаб X |
| scale_y | **float** | масштаб Y |



### См. также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`InkActions`](/slides/python-net/ru/aspose.slides.ink/inkactions)
* перечисление [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds)
* модуль [`aspose.slides.ink`](/slides/python-net/ru/aspose.slides.ink)
* библиотека [`Aspose.Slides`](/slides/python-net)