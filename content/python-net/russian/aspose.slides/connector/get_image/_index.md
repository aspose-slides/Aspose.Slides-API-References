---
title: get_image method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
Возвращает миниатюру формы.  
            По умолчанию используется тип границ миниатюры формы ShapeThumbnailBounds.Shape.

### Возврат

Миниатюра формы.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Возвращает миниатюру формы.

### Возврат

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
* класс [`Connector`](/slides/python-net/ru/aspose.slides/connector)
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* перечисление [`ShapeThumbnailBounds`](/slides/python-net/ru/aspose.slides/shapethumbnailbounds)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)