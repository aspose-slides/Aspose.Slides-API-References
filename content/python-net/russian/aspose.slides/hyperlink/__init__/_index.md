---
title: Hyperlink constructor
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Создает экземпляр гиперссылки.


```python
def __init__(self, url):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| url | **str** | URL гиперссылки. |


## __init__(self, slide) {#islide}
Создает экземпляр гиперссылки, указывающей на конкретный слайд.
Note: созданная гиперссылка должна быть назначена какому-то объекту из той же презентации, иначе ссылка будет сохранена как NoAction.


```python
def __init__(self, slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/ru/aspose.slides/islide) | Целевой слайд. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Создает экземпляр гиперссылки, используя другую гиперссылку в качестве источника, переопределяя вторичные свойства.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink) | Исходная гиперссылка |
| target_frame | **str** | Целевой фрейм |
| tooltip | **str** | Текст всплывающей подсказки |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### См. также
* класс [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)