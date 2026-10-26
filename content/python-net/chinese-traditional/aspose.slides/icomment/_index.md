---
title: IComment class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/icomment/
---
## IComment 類別

表示投影片上的註解。

IComment 型別公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`text`](/slides/python-net/zh-hant/aspose.slides/icomment/text/) | Returns or sets the plain text of a slide comment.<br/>            可讀寫 **str**. |
| [`created_time`](/slides/python-net/zh-hant/aspose.slides/icomment/created_time/) | Returns or sets the time of a comment creation.<br/>            Setting this property to **System.DateTime** means no comment time is set.<br/>            可讀寫 **System.DateTime**. |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/icomment/slide/) | Returns or sets the parent slide of a comment.<br/>            唯讀 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide). |
| [`author`](/slides/python-net/zh-hant/aspose.slides/icomment/author/) | Returns the author of a comment.<br/>            唯讀 [`ICommentAuthor`](/slides/python-net/zh-hant/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/zh-hant/aspose.slides/icomment/position/) | Returns or sets the position of a comment on a slide.<br/>            可讀寫 [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf). |
| [`parent_comment`](/slides/python-net/zh-hant/aspose.slides/icomment/parent_comment/) | Gets or sets parent comment.<br/>            可讀寫 [`IComment`](/slides/python-net/zh-hant/aspose.slides/icomment). |

## 方法

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides/icomment/remove/#) | Removes comment and all its replies from the parent collection. |

### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)