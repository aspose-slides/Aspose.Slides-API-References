---
title: split_text_by_columns method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/itextframe/split_text_by_columns/
weight: 70
---
## split_text_by_columns(self) {#}
Splits the text content of the [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe) into an array of strings,  
            where each element corresponds to a separate text column within the frame.

### 回傳值

字串陣列，每個字串代表 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe) 中特定欄位的文字內容。

```python
def split_text_by_columns(self):
    ...
```

### 備註

如果文字框未包含多個欄位，返回的陣列將只包含一個元素，內含完整的文字。  
            空的欄位將在陣列中以空字串表示。

### 另請參閱
* 類別 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)