---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/commentcollection/remove_at/
weight: 80
---
## remove_at(self, index) {#int}
移除集合中指定索引處的元素。


```python
def remove_at(self, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要移除的元素的零基索引。 |

### 例外情況

| 例外狀況 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小於 0，或索引大於或等於 Count |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果評論已被移除，則拋出此例外。 |



### 另請參閱
* 類別 [`CommentCollection`](/slides/python-net/zh-hant/aspose.slides/commentcollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)