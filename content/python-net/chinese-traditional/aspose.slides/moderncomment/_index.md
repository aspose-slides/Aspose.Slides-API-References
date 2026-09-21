---
title: ModernComment class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/moderncomment/
---
## ModernComment 類別

表示投影片上的評論。

**繼承:**[`ModernComment`](/slides/python-net/zh-hant/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/zh-hant/aspose.slides/comment)

ModernComment 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`text`](/slides/python-net/zh-hant/aspose.slides/moderncomment/text/) | 返回或設定投影片評論的純文字。<br/>            讀寫 **str**. |
| [`created_time`](/slides/python-net/zh-hant/aspose.slides/moderncomment/created_time/) | 返回或設定評論建立的時間。<br/>            將此屬性設定為 **System.DateTime** 表示未設定評論時間。<br/>            讀寫 **System.DateTime**. |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/moderncomment/slide/) | 返回或設定評論的父投影片。<br/>            唯讀 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide). |
| [`author`](/slides/python-net/zh-hant/aspose.slides/moderncomment/author/) | 返回評論的作者。<br/>            唯讀 [`ICommentAuthor`](/slides/python-net/zh-hant/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/zh-hant/aspose.slides/moderncomment/position/) | 返回或設定評論在投影片上的位置。<br/>            讀寫 **aspose.slides.PointF**. |
| [`parent_comment`](/slides/python-net/zh-hant/aspose.slides/moderncomment/parent_comment/) | 取得或設定父評論。<br/>            讀寫 [`IComment`](/slides/python-net/zh-hant/aspose.slides/icomment). |
| [`shape`](/slides/python-net/zh-hant/aspose.slides/moderncomment/shape/) | 返回與評論關聯的圖形。<br/>            唯讀 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/zh-hant/aspose.slides/moderncomment/text_selection_start/) | 取得或設定在與 AutoShape 關聯的評論之文字框中，文字選取的起始位置。<br/>            讀寫 **int**. |
| [`text_selection_length`](/slides/python-net/zh-hant/aspose.slides/moderncomment/text_selection_length/) | 取得或設定在與 AutoShape 關聯的評論之文字框中，文字選取的長度。<br/>            讀寫 **int**. |
| [`status`](/slides/python-net/zh-hant/aspose.slides/moderncomment/status/) | 取得或設定評論的狀態。<br/>            讀寫 [`ModernCommentStatus`](/slides/python-net/zh-hant/aspose.slides/moderncommentstatus). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides/moderncomment/remove/#) | 從父集合中移除評論及其所有回覆。 |

### 另請參閱
* 類別 [`Comment`](/slides/python-net/zh-hant/aspose.slides/comment)
* 類別 [`ModernComment`](/slides/python-net/zh-hant/aspose.slides/moderncomment)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)