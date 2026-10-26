---
title: write_font method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/embedallfontshtmlcontroller/write_font/
weight: 50
---
## write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data) {#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes}
將資料以 base64 的形式寫入 HTML 文件本身


```python
def write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator) | HTML 產生器 |
| original_font | [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata) | 要序列化的字型 |
| substituted_font | [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata) | 替代字型（如果發生字型替換），否則為 None |
| font_style | **str** | 字型樣式 |
| font_weight | **str** | 字型粗細 |
| font_data | **bytes** | 字型資料 |



### 另請參閱
* 類別 [`EmbedAllFontsHtmlController`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller)
* 類別 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata)
* 類別 [`IHtmlGenerator`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)