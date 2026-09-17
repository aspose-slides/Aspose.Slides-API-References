---
title: write_shape_start method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Вызывается перед рендерингом формы. Вызывается один раз для каждой формы. Если эта функция записывает что-либо в generator, текущая генерация изображения слайда будет завершена, добавленный HTML-фрагмент будет вставлен, и новое изображение будет начато поверх предыдущего.

```python
def write_shape_start(self, generator, shape):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator) | Объект вывода. |
| shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Форма, которая собирается отрисовываться. |

### См. также
* класс [`EmbedAllFontsHtmlController`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller)
* класс [`IHtmlGenerator`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator)
* класс [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)