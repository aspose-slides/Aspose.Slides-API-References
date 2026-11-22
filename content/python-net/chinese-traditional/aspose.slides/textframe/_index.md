---
title: TextFrame class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/textframe/
---
## TextFrame 類別

表示一個 TextFrame。

TextFrame 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`paragraphs`](/slides/python-net/zh-hant/aspose.slides/textframe/paragraphs/) | 返回框架中所有段落的列表。<br/>            唯讀 [`IParagraphCollection`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/zh-hant/aspose.slides/textframe/text/) | 取得或設定 TextFrame 的純文字。<br/>            讀寫 **str**. |
| [`text_frame_format`](/slides/python-net/zh-hant/aspose.slides/textframe/text_frame_format/) | 返回此 TextFrame 物件的格式化物件。<br/>            唯讀 [`ITextFrameFormat`](/slides/python-net/zh-hant/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/textframe/hyperlink_queries/) | 提供對所含超連結的簡易存取。<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/textframe/slide/) | 返回 TextFrame 的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/textframe/presentation/) | 返回 TextFrame 的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/zh-hant/aspose.slides/textframe/parent_shape/) | 返回父形狀，若父物件未實作 IShape 介面則返回 None<br/>            唯讀 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/zh-hant/aspose.slides/textframe/parent_cell/) | 返回父儲存格，若父物件未實作 ICell 介面則返回 None。<br/>            唯讀 [`ICell`](/slides/python-net/zh-hant/aspose.slides/icell). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | 以指定的顏色突顯樣本文本的所有匹配項目。 |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/zh-hant/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | 以指定的顏色突顯樣本文本的所有匹配項目。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh-hant/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | 以指定的顏色突顯樣本文本的所有匹配項目。 |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/zh-hant/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | 以指定的顏色突顯正則表達式的所有匹配項目。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | 以指定的顏色突顯正則表達式的所有匹配項目。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/textframe/join_portions_with_same_formatting/#) | 合併所有段落中具有相同格式的文字串。 |
| [`split_text_by_columns(self)`](/slides/python-net/zh-hant/aspose.slides/textframe/split_text_by_columns/#) | 將 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe) 的文字內容分割成字串陣列，<br/>            其中每個元素對應於框架內的單一文字欄。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh-hant/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 將所有指定文字的出現置換為另一個指定文字。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh-hant/aspose.slides/textframe/replace_regex/#str-str) | 將正則表達式的所有匹配項目替換為指定字串。 |
| [`get_text_rect(self)`](/slides/python-net/zh-hant/aspose.slides/textframe/get_text_rect/#) | 取得父形狀幾何形狀所定義的文字矩形。 |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)