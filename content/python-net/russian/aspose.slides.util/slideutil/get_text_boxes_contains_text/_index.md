---
title: get_text_boxes_contains_text method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
Возвращает все текстовые рамки на указанном слайде, содержащие заданный текст.

### Возвращаемое значение

Массив объектов [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe), содержащих указанный текст.



```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide) | Слайд для поиска. |
| text | **str** | Текст для поиска внутри текстовых рамок. |
| check_placeholder_text | **bool** | Указывает, следует ли включать пустые текстовые рамки, у которых текст заполнителя содержит искомый текст. |



### См. также
* класс [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide)
* класс [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe)
* класс [`SlideUtil`](/slides/python-net/ru/aspose.slides.util/slideutil)
* модуль [`aspose.slides.util`](/slides/python-net/ru/aspose.slides.util)
* библиотека [`Aspose.Slides`](/slides/python-net)