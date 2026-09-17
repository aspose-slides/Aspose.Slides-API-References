---
title: write_shape_end method
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Вызывается перед отрисовкой shape. Вызывается один раз для каждой shape. Если эта функция записывает что-либо в generator, текущая генерация изображения слайда будет завершена, добавленный html-фрагмент будет вставлен, и новое изображение начнётся поверх предыдущего.

```python
def write_shape_end(self, generator, shape):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator) | Объект вывода. |
| shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Фигура, которая отрисовывается последней. |

### См. также
* класс [`EmbedAllFontsHtmlController`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller)
* класс [`IHtmlGenerator`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator)
* класс [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)