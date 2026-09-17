---
title: find_and_replace_text method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.util/slideutil/find_and_replace_text/
weight: 20
---
## find_and_replace_text(presentation, with_masters, find, replace, format) {#ipresentation-bool-str-str-portionformat}
Находит и заменяет текст в презентации с заданным форматом


```python
@staticmethod
def find_and_replace_text(presentation, with_masters, find, replace, format):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation) | Сканированная презентация. |
| with_masters | **bool** | Определяет, следует ли сканировать мастер-слайды. |
| find | **str** | Строковое значение для поиска. |
| replace | **str** | Строковое значение для замены. |
| format | [`PortionFormat`](/slides/python-net/ru/aspose.slides/portionformat) | Формат для замены части текста. Если None, будет использован формат первого <br/><br/>            символа найденной строки. |



### См. также
* класс [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation)
* класс [`PortionFormat`](/slides/python-net/ru/aspose.slides/portionformat)
* класс [`SlideUtil`](/slides/python-net/ru/aspose.slides.util/slideutil)
* модуль [`aspose.slides.util`](/slides/python-net/ru/aspose.slides.util)
* библиотека [`Aspose.Slides`](/slides/python-net)