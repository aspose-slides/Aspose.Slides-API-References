---
title: slide_number_format property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/markdownsaveoptions/slide_number_format/
weight: 160
---
## slide_number_format 屬性
取得或設定在 Markdown 輸出中用於投影片編號標題的格式字串。
            格式必須包含「{0}」佔位符，於匯出時會被取代為投影片索引。
            範例："# Slide {0}" 會產生 "# Slide 1"、"# Slide 2" 等。

### 定義:
```python
@property
def slide_number_format(self):
    ...

@slide_number_format.setter
def slide_number_format(self, value):
    ...
```

### 另見
* 類別 [`MarkdownSaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)