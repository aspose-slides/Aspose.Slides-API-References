---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/commentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
移除集合中指定索引處的作者。

```python
def remove_at(self, index):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要移除之元素的零基索引。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小於 0，或索引大於或等於 Count |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果作者已被移除，則拋出此例外。 |

### 另見
* 類別 [`CommentAuthorCollection`](/slides/python-net/zh-hant/aspose.slides/commentauthorcollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)