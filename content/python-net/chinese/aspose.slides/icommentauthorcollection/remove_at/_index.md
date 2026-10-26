---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icommentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
从集合中删除指定索引位置的作者。

```python
def remove_at(self, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要删除的元素的零基索引。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小于 0 或 索引大于或等于 Count |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 已经删除的作者将导致抛出此异常。 |

### 另见
* 类 [`ICommentAuthorCollection`](/slides/python-net/zh/aspose.slides/icommentauthorcollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)