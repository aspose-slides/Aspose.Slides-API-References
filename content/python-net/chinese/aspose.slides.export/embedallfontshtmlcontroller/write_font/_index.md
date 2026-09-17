---
title: write_font method
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/embedallfontshtmlcontroller/write_font/
weight: 50
---
## write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data) {#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes}
将数据以 base64 形式写入 HTML 文档本身

```python
def write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/zh/aspose.slides.export/ihtmlgenerator) | HTML 生成器 |
| original_font | [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata) | 要序列化的字体 |
| substituted_font | [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata) | 被替换的字体（如果发生了字体替换），否则为 None |
| font_style | **str** | 字体样式 |
| font_weight | **str** | 字体粗细 |
| font_data | **bytes** | 字体数据 |

### 另见
* 类 [`EmbedAllFontsHtmlController`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller)
* 类 [`IFontData`](/slides/python-net/zh/aspose.slides/ifontdata)
* 类 [`IHtmlGenerator`](/slides/python-net/zh/aspose.slides.export/ihtmlgenerator)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)