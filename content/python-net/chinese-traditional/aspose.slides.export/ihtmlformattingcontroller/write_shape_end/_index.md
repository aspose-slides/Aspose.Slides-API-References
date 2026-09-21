---
title: write_shape_end method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
在形狀渲染之前呼叫。每個形狀僅呼叫一次。如果此函式向 generator 寫入任何內容，則當前投影片影像的產生將結束，插入已加入的 HTML 片段，並在先前的影像之上開始產生新影像。

```python
def write_shape_end(self, generator, shape):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator) | 輸出物件。 |
| shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 最後渲染的形狀。 |

### 另請參閱
* 類別 [`IHtmlFormattingController`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlformattingcontroller)
* 類別 [`IHtmlGenerator`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator)
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)