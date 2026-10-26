---
title: write_font method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/embedallfontshtmlcontroller/write_font/
weight: 50
---
## write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data) {#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes}
Записывает данные в формате base64 непосредственно в HTML-документ


```python
def write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator) | генератор HTML |
| original_font | [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata) | Шрифт для сериализации |
| substituted_font | [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata) | Заменённый шрифт (если произошла замена шрифта), None иначе |
| font_style | **str** | Стиль шрифта |
| font_weight | **str** | Толщина шрифта |
| font_data | **bytes** | Данные шрифта |



### См. также
* класс [`EmbedAllFontsHtmlController`](/slides/python-net/ru/aspose.slides.export/embedallfontshtmlcontroller)
* класс [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata)
* класс [`IHtmlGenerator`](/slides/python-net/ru/aspose.slides.export/ihtmlgenerator)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)