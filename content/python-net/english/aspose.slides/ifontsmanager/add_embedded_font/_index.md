---
title: add_embedded_font method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ifontsmanager/add_embedded_font/
weight: 10
---


## add_embedded_font {#asposeslidesifontdata-asposeslidesexportembedfontcharacters}
Adds the embedded font.
Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of 
            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is None or this font is already embedded


```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/aspose.slides/ifontdata) | Font data object [`IFontData`](/slides/python-net/aspose.slides/ifontdata) |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/aspose.slides.export/embedfontcharacters) | Embedded font rule [`EmbedFontCharacters`](/slides/python-net/aspose.slides.export/embedfontcharacters) |


## add_embedded_font {#bytes-asposeslidesexportembedfontcharacters}
Adds the embedded font
Keep in mind when adding any fonts that most fonts are copyrighted. First locate the license of 
            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is None or this font is already embedded


```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| font_data | **bytes** | Font data **int**[] |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/aspose.slides.export/embedfontcharacters) | Embedded font rule [`EmbedFontCharacters`](/slides/python-net/aspose.slides.export/embedfontcharacters) |



### See Also
* enumeration [`EmbedFontCharacters`](/slides/python-net/aspose.slides.export/embedfontcharacters)
* class [`IFontData`](/slides/python-net/aspose.slides/ifontdata)
* class [`IFontsManager`](/slides/python-net/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

