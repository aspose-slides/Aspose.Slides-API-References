---
title: remove method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icommentcollection/remove/
weight: 60
---
## remove(self, comment) {#icomment}
删除集合中指定评论的第一次出现。

```python
def remove(self, comment):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/zh/aspose.slides/icomment) | 要从集合中删除的评论。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 comment 为 `None` |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果 comment 已经被移除则抛出。 |

### 参见
* 类 [`IComment`](/slides/python-net/zh/aspose.slides/icomment)
* 类 [`ICommentCollection`](/slides/python-net/zh/aspose.slides/icommentcollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)