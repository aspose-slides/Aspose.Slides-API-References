---
title: remove_at method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/icommentcollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
移除集合中指定索引位置的元素。

```python
def remove_at(self, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 要移除之元素的零基索引。 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小於 0 或索引大於等於 Count |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 若評論已被移除則拋出此例外。 |

### 另請參閱
* 類別 [`ICommentCollection`](/slides/python-net/zh-hant/aspose.slides/icommentcollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)