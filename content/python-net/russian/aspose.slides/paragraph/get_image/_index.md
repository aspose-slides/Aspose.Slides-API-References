---
title: get_image method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
Возвращает изображение абзаца.

### Возвращаемое значение

Изображение, содержащее отрисованный абзац, или **None**
             если абзац не может быть найден в своей родительской коллекции, не имеет действительных границ отрисовки или произошла ошибка при рендеринге изображения.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Возвращает изображение абзаца с указанным масштабом.

### Возвращаемое значение

Изображение, содержащее отрисованный абзац, или **None**
             если абзац не может быть найден в своей родительской коллекции, не имеет действительных границ отрисовки или произошла ошибка при рендеринге изображения.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| scale_x | **float** | Горизонтальный коэффициент масштабирования, применяемый к изображению абзаца. |
| scale_y | **float** | Вертикальный коэффициент масштабирования, применяемый к изображению абзаца. |



### См. также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`Paragraph`](/slides/python-net/ru/aspose.slides/paragraph)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)