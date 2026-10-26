---
title: write_shape_start method
second_title: Aspose.Slides 用於 Python 的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
在 shape 的渲染之前呼叫。 在每個 shape 上僅呼叫一次。如果此函式向 generator 寫入任何內容，則當前投影片影像的產生將結束，加入的 html 片段會被插入，並且會在先前的影像之上開始產生新影像。

```python
def write_shape_start(self, generator, shape):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator) | Output object. |
| shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | Shape which is about to render. |

### 另請參閱
* 類別 [`IHtmlFormattingController`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlformattingcontroller)
* 類別 [`IHtmlGenerator`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator)
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)