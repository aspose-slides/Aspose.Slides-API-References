---
title: add_embedded_font method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ifontsmanager/add_embedded_font/
weight: 10
---
## add_embedded_font(self, font_data, embed_font_rule) {#ifontdata-asposeslidesexportembedfontcharacters}
加入內嵌字型。
            請記住，當複製任何字型時，大多數字型均受版權保護。請先找出字型的授權，並確認它們可以自由轉移到其他機器。如果 font data 為 None 或此字型已經嵌入，將拋出 ArgumentException。

```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata) | Font data 物件 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata) |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/zh-hant/aspose.slides.export/embedfontcharacters) | Embedded font rule [`EmbedFontCharacters`](/slides/python-net/zh-hant/aspose.slides.export/embedfontcharacters) |

## add_embedded_font(self, font_data, embed_font_rule) {#bytes-asposeslidesexportembedfontcharacters}
加入內嵌字型
            請記住，當新增任何字型時，大多數字型均受版權保護。請先找出字型的授權，並確認它們可以自由轉移到其他機器。如果 font data 為 None 或此字型已經嵌入，將拋出 ArgumentException。

```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| font_data | **bytes** | Font data **int**[] |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/zh-hant/aspose.slides.export/embedfontcharacters) | Embedded font rule [`EmbedFontCharacters`](/slides/python-net/zh-hant/aspose.slides.export/embedfontcharacters) |

### 另見
* 列舉 [`EmbedFontCharacters`](/slides/python-net/zh-hant/aspose.slides.export/embedfontcharacters)
* 類別 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata)
* 類別 [`IFontsManager`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)