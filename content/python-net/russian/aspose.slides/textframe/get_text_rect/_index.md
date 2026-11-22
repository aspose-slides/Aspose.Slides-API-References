---
title: get_text_rect method
second_title: Aspose.Slides для Python через .NET справка API
description: 
type: docs
url: /ru/aspose.slides/textframe/get_text_rect/
weight: 10
---
## get_text_rect(self) {#}
Получает прямоугольник текста, определяемый геометрией родительской формы.

### Возвращаемое значение

Объект [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef), определяющий текстовую область.



```python
def get_text_rect(self):
    ...
```


### Примечания

Координаты прямоугольника задаются относительно левого верхнего угла родительской формы.

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Текстовая рамка не связана с геометрической фигурой. |



### См. также
* класс [`TextFrame`](/slides/python-net/ru/aspose.slides/textframe)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)