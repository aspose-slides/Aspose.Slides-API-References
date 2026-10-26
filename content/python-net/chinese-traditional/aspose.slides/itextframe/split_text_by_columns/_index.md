---
title: split_text_by_columns method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/itextframe/split_text_by_columns/
weight: 60
---
## split_text_by_columns(self) {#}
將 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe) 的文字內容分割成字串陣列，  
            每個元素對應框架內的個別文字欄位。

### Returns

字串陣列，  
            其中每個字串代表 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe) 中特定欄位的文字內容。

```python
def split_text_by_columns(self):
    ...
```

### Remarks

如果文字框未包含多個欄位，回傳的陣列將僅有一個包含完整文字的元素。  
            空的欄位將以空字串表示於陣列中。

### See Also
* class [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe)
* module [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)