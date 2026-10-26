---
title: get_image method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image(self) {#}
Возвращает изображение параграфа.

### Возвращает

Изображение, содержащее отрисованный параграф, или **None**
             если параграф не найден в своей родительской коллекции, не имеет допустимых
             границ отрисовки или произошла ошибка при отрисовке изображения.



```python
def get_image(self):
    ...
```



## get_image(self, scale_x, scale_y) {#float-float}
Возвращает изображение параграфа с указанным масштабом.

### Возвращает

Изображение, содержащее отрисованный параграф, или **None**
             если параграф не найден в своей родительской коллекции, не имеет допустимых
             границ отрисовки или произошла ошибка при отрисовке изображения.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| scale_x | **float** | Горизонтальный коэффициент масштабирования, применяемый к изображению параграфа. |
| scale_y | **float** | Вертикальный коэффициент масштабирования, применяемый к изображению параграфа. |



### См. также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`IParagraph`](/slides/python-net/ru/aspose.slides/iparagraph)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)