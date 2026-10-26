---
title: add_author method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/icommentauthorcollection/add_author/
weight: 10
---
## add_author(self, name, initials) {#str-str}
在集合的末端新增作者。

### 返回

新的 [`ICommentAuthor`](/slides/python-net/zh-hant/aspose.slides/icommentauthor) 物件。



```python
def add_author(self, name, initials):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| name | **str** | 新作者的名稱。 |
| initials | **str** | 新作者的縮寫。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果已經加入具有相同名稱和縮寫的作者，則拋出此例外。 |



### 另見
* 類別 [`ICommentAuthor`](/slides/python-net/zh-hant/aspose.slides/icommentauthor)
* 類別 [`ICommentAuthorCollection`](/slides/python-net/zh-hant/aspose.slides/icommentauthorcollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)