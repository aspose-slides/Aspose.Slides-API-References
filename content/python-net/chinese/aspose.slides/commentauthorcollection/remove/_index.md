---
title: remove method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/commentauthorcollection/remove/
weight: 50
---
## remove(self, author) {#icommentauthor}
删除集合中指定作者的第一次出现。


```python
def remove(self, author):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| author | [`ICommentAuthor`](/slides/python-net/zh/aspose.slides/icommentauthor) | 要从集合中删除的作者。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 作者为 `None` |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果作者已经被删除，则抛出。 |



### 另请参见
* 类 [`CommentAuthorCollection`](/slides/python-net/zh/aspose.slides/commentauthorcollection)
* 类 [`ICommentAuthor`](/slides/python-net/zh/aspose.slides/icommentauthor)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)