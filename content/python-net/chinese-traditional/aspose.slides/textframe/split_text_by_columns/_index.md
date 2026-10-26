---
title: split_text_by_columns method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/textframe/split_text_by_columns/
weight: 60
---
## split_text_by_columns(self) {#}
將 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe) 的文字內容拆分為字串陣列，  
            每個元素對應框架內的單獨文字欄位。

### 返回
字串陣列，其中每個字串代表 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe) 中特定欄位的文字內容。


```python
def split_text_by_columns(self):
    ...
```


### 備註
如果文字框未包含多個欄位，返回的陣列將僅有一個包含完整文字的元素。  
            空欄位將以空字串形式出現在陣列中。


### 另見
* 類別 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe)
* 類別 [`TextFrame`](/slides/python-net/zh-hant/aspose.slides/textframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)