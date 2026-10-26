---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/commentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
从集合中移除指定索引处的作者。

```python
def remove_at(self, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要移除元素的零基索引。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小于 0 或索引大于等于 Count |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果作者已经被移除则抛出。 |

### 另见
* 类 [`CommentAuthorCollection`](/slides/python-net/zh/aspose.slides/commentauthorcollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)