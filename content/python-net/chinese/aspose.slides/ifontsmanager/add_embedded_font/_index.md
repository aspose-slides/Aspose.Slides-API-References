---
title: add_embedded_font method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ifontsmanager/add_embedded_font/
weight: 10
---
## add_embedded_font(self, font_data, embed_font_rule) {#ifontdata-asposeslidesexportembedfontcharacters}
添加嵌入的字体。
请注意，在复制任何字体时，大多数字体都有版权。首先提前查找字体的许可证，并验证它们是否可以自由转移到另一台机器上。如果 font data 为 None 或此字体已嵌入，则会抛出 ArgumentException。

```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata) | 字体数据对象 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata) |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/zh/aspose.slides.export/embedfontcharacters) | 嵌入字体规则 [`EmbedFontCharacters`](/slides/python-net/zh/aspose.slides.export/embedfontcharacters) |

## add_embedded_font(self, font_data, embed_font_rule) {#bytes-asposeslidesexportembedfontcharacters}
添加嵌入的字体
请注意，在添加任何字体时，大多数字体都有版权。首先提前查找字体的许可证，并验证它们是否可以自由转移到另一台机器上。如果 font data 为 None 或此字体已嵌入，则会抛出 ArgumentException。

```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_data | **bytes** | Font data **int**[] |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/zh/aspose.slides.export/embedfontcharacters) | 嵌入字体规则 [`EmbedFontCharacters`](/slides/python-net/zh/aspose.slides.export/embedfontcharacters) |

### 另请参阅
* 枚举 [`EmbedFontCharacters`](/slides/python-net/zh/aspose.slides.export/embedfontcharacters)
* 类 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)
* 类 [`IFontsManager`](/slides/python-net/zh/aspose.slides/ifontsmanager)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)