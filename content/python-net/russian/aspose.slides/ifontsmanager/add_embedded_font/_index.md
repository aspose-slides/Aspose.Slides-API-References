---
title: add_embedded_font method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/ifontsmanager/add_embedded_font/
weight: 10
---
## add_embedded_font(self, font_data, embed_font_rule) {#ifontdata-asposeslidesexportembedfontcharacters}
Adds the embedded font.
            Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of 
            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is None or this font is already embedded

```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata) | Объект данных шрифта [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata) |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/ru/aspose.slides.export/embedfontcharacters) | Правило встраивания шрифта [`EmbedFontCharacters`](/slides/python-net/ru/aspose.slides.export/embedfontcharacters) |

## add_embedded_font(self, font_data, embed_font_rule) {#bytes-asposeslidesexportembedfontcharacters}
Adds the embedded font
            Keep in mind when adding any fonts that most fonts are copyrighted. First locate the license of 
            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is None or this font is already embedded

```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_data | **bytes** | Данные шрифта **int**[] |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/ru/aspose.slides.export/embedfontcharacters) | Правило встраивания шрифта [`EmbedFontCharacters`](/slides/python-net/ru/aspose.slides.export/embedfontcharacters) |

### См. также
* перечисление [`EmbedFontCharacters`](/slides/python-net/ru/aspose.slides.export/embedfontcharacters)
* класс [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata)
* класс [`IFontsManager`](/slides/python-net/ru/aspose.slides/ifontsmanager)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)