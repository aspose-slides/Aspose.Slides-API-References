---
title: write_shape_end method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
在 shape 的渲染之前被呼叫。對每個 shape 僅呼叫一次。如果此函式寫入任何內容到 generator，則目前的投影片影像生成將結束，加入的 html 片段會被插入，並且會在先前的影像上方啟動新的影像。

```python
def write_shape_end(self, generator, shape):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator) | 輸出物件。 |
| shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 最後被渲染的 Shape。 |

### 另請參閱
* 類別 [`EmbedAllFontsHtmlController`](/slides/python-net/zh-hant/aspose.slides.export/embedallfontshtmlcontroller)
* 類別 [`IHtmlGenerator`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator)
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)