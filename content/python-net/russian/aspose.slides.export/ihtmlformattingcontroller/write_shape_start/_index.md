---
title: write_shape_start method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-либо в generator, текущая генерация изображения слайда будет завершена, добавленный html-фрагмент вставлен и новое изображение будет начато поверх предыдущего.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator) | Объект вывода. |
| shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Фигура, которая собирается отрисовываться. |



### См. также
* class [`IHtmlFormattingController`](/slides/python-net/ru/aspose.slides.export/ihtmlformattingcontroller)
* class [`IHtmlGenerator`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator)
* class [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* module [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)