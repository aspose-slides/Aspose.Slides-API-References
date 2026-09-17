---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/commentcollection/remove_at/
weight: 80
---
## remove_at(self, index) {#int}
从集合中删除指定索引处的元素。

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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小于 0 或索引大于或等于 Count |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果评论已被删除则抛出。 |

### 另请参见
* 类 [`CommentCollection`](/slides/python-net/zh/aspose.slides/commentcollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)