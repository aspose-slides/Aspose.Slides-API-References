---
title: add_author method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/commentauthorcollection/add_author/
weight: 10
---
## add_author(self, name, initials) {#str-str}
在集合末尾添加新作者。

### 返回值

新 [`ICommentAuthor`](/slides/python-net/zh/aspose.slides/icommentauthor) 对象。

```python
def add_author(self, name, initials):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | **str** | 新作者的名称。 |
| initials | **str** | 新作者的缩写。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果已添加具有相同名称和缩写的作者，则抛出此异常。 |

### 参见
* 类 [`CommentAuthorCollection`](/slides/python-net/zh/aspose.slides/commentauthorcollection)
* 类 [`ICommentAuthor`](/slides/python-net/zh/aspose.slides/icommentauthor)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)