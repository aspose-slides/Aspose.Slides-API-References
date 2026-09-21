---
title: remove method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/icommentauthorcollection/remove/
weight: 50
---
## remove(self, author) {#icommentauthor}
從集合中移除指定作者的第一次出現。

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
| **RuntimeError(Proxy error(ArgumentNullException))** | 作者為 `None` |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果作者已被移除則拋出此例外。 |

### 另見
* 類別 [`ICommentAuthor`](/slides/python-net/zh-hant/aspose.slides/icommentauthor)
* 類別 [`ICommentAuthorCollection`](/slides/python-net/zh-hant/aspose.slides/icommentauthorcollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)