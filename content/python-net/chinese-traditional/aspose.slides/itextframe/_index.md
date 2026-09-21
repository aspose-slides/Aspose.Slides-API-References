---
title: ITextFrame class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/itextframe/
---
## ITextFrame 類別

Represents a TextFrame.

The ITextFrame type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/zh-hant/aspose.slides/itextframe/paragraphs/) | 返回框架中所有段落的列表。<br/>            唯讀 [`IParagraphCollection`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection)。 |
| [`text`](/slides/python-net/zh-hant/aspose.slides/itextframe/text/) | 取得或設定 TextFrame 的純文字。<br/>            可讀寫 **str**。 |
| [`text_frame_format`](/slides/python-net/zh-hant/aspose.slides/itextframe/text_frame_format/) | 返回此 TextFrame 物件的格式化物件。<br/>            唯讀 [`ITextFrameFormat`](/slides/python-net/zh-hant/aspose.slides/itextframeformat)。 |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/itextframe/hyperlink_queries/) | 提供對所含超連結的便利存取。<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries)。 |
| [`parent_shape`](/slides/python-net/zh-hant/aspose.slides/itextframe/parent_shape/) | 返回父形狀；若父物件未實作 IShape 介面則返回 None。<br/>            唯讀 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |
| [`parent_cell`](/slides/python-net/zh-hant/aspose.slides/itextframe/parent_cell/) | 返回父儲存格；若父物件未實作 ICell 介面則返回 None。<br/>            唯讀 [`ICell`](/slides/python-net/zh-hant/aspose.slides/icell)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/itextframe/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | 以指定的顏色突顯樣本文本的所有匹配項目。 |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/zh-hant/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | 以指定的顏色突顯樣本文本的所有匹配項目。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh-hant/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | 以指定的顏色突顯樣本文本的所有匹配項目。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | 以指定的顏色突顯正規表達式的所有匹配項目。 |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/zh-hant/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | 以指定的顏色突顯正規表達式的所有匹配項目。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/itextframe/join_portions_with_same_formatting/#) | 在所有段落中合併具有相同格式的文字跑段。 |
| [`split_text_by_columns(self)`](/slides/python-net/zh-hant/aspose.slides/itextframe/split_text_by_columns/#) | 將 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe) 的文字內容分割成字串陣列，<br/>            其中每個元素對應框架內的單獨文字欄位。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh-hant/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 將所有指定文字的出現取代為另一個指定文字。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh-hant/aspose.slides/itextframe/replace_regex/#str-str) | 將正規表達式的所有匹配項目取代為指定字串。 |


### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)