---
title: remove_at method
second_title: Aspose.Slides for Python 通过 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icommentcollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
移除集合中指定索引处的元素。

```python
def remove_at(self, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要移除的元素的零基索引。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小于 0，或索引大于等于 Count |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果评论已被移除，则抛出此异常。 |

### 另请参见
* 类 [`ICommentCollection`](/slides/python-net/zh/aspose.slides/icommentcollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)