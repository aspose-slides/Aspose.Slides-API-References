---
title: add_author method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icommentauthorcollection/add_author/
weight: 10
---
## add_author(self, name, initials) {#str-str}
在集合末尾添加新作者。

### 返回

新的 [`ICommentAuthor`](/slides/python-net/zh/aspose.slides/icommentauthor) 对象。



```python
def add_author(self, name, initials):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | **str** | 新作者的名称。 |
| initials | **str** | 新作者的首字母。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果已经添加了相同名称和首字母的作者，则抛出此异常。 |



### 另请参阅
* 类 [`ICommentAuthor`](/slides/python-net/zh/aspose.slides/icommentauthor)
* 类 [`ICommentAuthorCollection`](/slides/python-net/zh/aspose.slides/icommentauthorcollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)