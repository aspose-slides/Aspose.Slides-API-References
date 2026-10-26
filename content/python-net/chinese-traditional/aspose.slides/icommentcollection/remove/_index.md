---
title: remove method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/icommentcollection/remove/
weight: 60
---
## remove(self, comment) {#icomment}
移除集合中指定註解的第一次出現。

```python
def remove(self, comment):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/zh-hant/aspose.slides/icomment) | 要從集合中移除的註解。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 comment 為 `None` |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果 comment 已經被移除，則拋出此例外。 |

### 參見
* 類別 [`IComment`](/slides/python-net/zh-hant/aspose.slides/icomment)
* 類別 [`ICommentCollection`](/slides/python-net/zh-hant/aspose.slides/icommentcollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)