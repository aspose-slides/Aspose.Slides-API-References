---
title: remove method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/commentauthorcollection/remove/
weight: 50
---
## remove(self, author) {#icommentauthor}
移除集合中指定作者的第一個出現。

```python
def remove(self, author):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| author | [`ICommentAuthor`](/slides/python-net/zh-hant/aspose.slides/icommentauthor) | 要從集合中移除的作者。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Author 為 `None` |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果 author 已經被移除，則拋出。 |

### 另見
* 類別 [`CommentAuthorCollection`](/slides/python-net/zh-hant/aspose.slides/commentauthorcollection)
* 類別 [`ICommentAuthor`](/slides/python-net/zh-hant/aspose.slides/icommentauthor)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)