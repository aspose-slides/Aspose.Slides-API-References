---
title: get_image method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chart/get_image/
weight: 40
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
* класс [`Chart`](/slides/python-net/ru/aspose.slides.charts/chart)
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* перечисление [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)