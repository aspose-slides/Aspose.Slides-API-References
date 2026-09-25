---
title: ModernComment class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/moderncomment/
---
## ModernComment 類別

表示投影片上的批註。

**繼承:**[`ModernComment`](/slides/python-net/zh-hant/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/zh-hant/aspose.slides/comment)

ModernComment 類型公開以下成員：

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`text`](/slides/python-net/zh-hant/aspose.slides/moderncomment/text/) | 返回或設定投影片批註的純文字。<br/>            讀/寫 **str**. |
| [`created_time`](/slides/python-net/zh-hant/aspose.slides/moderncomment/created_time/) | 返回或設定批註建立的時間。<br/>            將此屬性設為 **System.DateTime** 表示未設定批註時間。<br/>            讀/寫 **System.DateTime**. |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/moderncomment/slide/) | 返回或設定批註的父投影片。<br/>            唯讀 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide). |
| [`author`](/slides/python-net/zh-hant/aspose.slides/moderncomment/author/) | 返回批註的作者。<br/>            唯讀 [`ICommentAuthor`](/slides/python-net/zh-hant/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/zh-hant/aspose.slides/moderncomment/position/) | 返回或設定批註在投影片上的位置。<br/>            讀/寫 [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf). |
| [`parent_comment`](/slides/python-net/zh-hant/aspose.slides/moderncomment/parent_comment/) | 取得或設定父批註。<br/>            讀/寫 [`IComment`](/slides/python-net/zh-hant/aspose.slides/icomment). |
| [`shape`](/slides/python-net/zh-hant/aspose.slides/moderncomment/shape/) | 返回與批註相關聯的形狀。<br/>            唯讀 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/zh-hant/aspose.slides/moderncomment/text_selection_start/) | 取得或設定文字框中選取文字的起始位置（若批註與 AutoShape 相關聯）。<br/>            讀/寫 **int**. |
| [`text_selection_length`](/slides/python-net/zh-hant/aspose.slides/moderncomment/text_selection_length/) | 取得或設定文字框中選取文字的長度（若批註與 AutoShape 相關聯）。<br/>            讀/寫 **int**. |
| [`status`](/slides/python-net/zh-hant/aspose.slides/moderncomment/status/) | 取得或設定批註的狀態。<br/>            讀/寫 [`ModernCommentStatus`](/slides/python-net/zh-hant/aspose.slides/moderncommentstatus). |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides/moderncomment/remove/#) | 從父集合中移除批註及其所有回覆。 |

### 另請參閱
* 類別 [`Comment`](/slides/python-net/zh-hant/aspose.slides/comment)
* 類別 [`ModernComment`](/slides/python-net/zh-hant/aspose.slides/moderncomment)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)