---
title: get_image method
second_title: Aspose.Slides для Python через .NET API
description: 
type: docs
url: /ru/aspose.slides/audioframe/get_image/
weight: 50
---
## get_image(self) {#}
Возвращает миниатюру формы.
ShapeThumbnailBounds.Shape тип границ миниатюры формы используется по умолчанию.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds) | Тип границ ShapeThumbnailBounds. |
| scale_x | **float** | Масштаб X |
| scale_y | **float** | Масштаб Y |



### Смотрите также
* класс [`AudioFrame`](/slides/python-net/ru/aspose.slides/audioframe)
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* перечисление [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)