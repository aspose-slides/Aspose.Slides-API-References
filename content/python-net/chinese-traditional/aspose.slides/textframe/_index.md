---
title: TextFrame class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/textframe/
---
## TextFrame 類別

表示 TextFrame。

TextFrame 型別公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`paragraphs`](/slides/python-net/zh-hant/aspose.slides/textframe/paragraphs/) | 返回框架中所有段落的列表。<br/>            只讀 [`IParagraphCollection`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection)。 |
| [`text`](/slides/python-net/zh-hant/aspose.slides/textframe/text/) | 取得或設定 TextFrame 的純文字。<br/>            可讀寫 **str**。 |
| [`text_frame_format`](/slides/python-net/zh-hant/aspose.slides/textframe/text_frame_format/) | 返回此 TextFrame 物件的格式設定物件。<br/>            只讀 [`ITextFrameFormat`](/slides/python-net/zh-hant/aspose.slides/itextframeformat)。 |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/textframe/hyperlink_queries/) | 提供對所含超連結的簡易存取。<br/>            只讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/textframe/slide/) | 返回 TextFrame 所屬的投影片。<br/>            只讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/textframe/presentation/) | 返回 TextFrame 所屬的簡報。<br/>            只讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`parent_shape`](/slides/python-net/zh-hant/aspose.slides/textframe/parent_shape/) | 返回父形狀；如果父物件未實作 IShape 介面則返回 None<br/>            只讀 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。 |
| [`parent_cell`](/slides/python-net/zh-hant/aspose.slides/textframe/parent_cell/) | 返回父儲存格；如果父物件未實作 ICell 介面則返回 None。<br/>            只讀 [`ICell`](/slides/python-net/zh-hant/aspose.slides/icell)。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | 以指定的顏色突顯樣本文字的所有符合項目。 |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/zh-hant/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | 以指定的顏色突顯樣本文字的所有符合項目。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh-hant/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | 以指定的顏色突顯樣本文字的所有符合項目。 |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/zh-hant/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | 以指定的顏色突顯正規表達式的所有符合項目。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | 以指定的顏色突顯正規表達式的所有符合項目。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/textframe/join_portions_with_same_formatting/#) | 將所有段落中具有相同格式的文字執行合併。 |
| [`split_text_by_columns(self)`](/slides/python-net/zh-hant/aspose.slides/textframe/split_text_by_columns/#) | 將 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe) 的文字內容分割為字串陣列，<br/>            其中每個元素對應框架內的單獨文字欄。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh-hant/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 將指定文字的所有出現替換為另一個指定文字。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh-hant/aspose.slides/textframe/replace_regex/#str-str) | 將正規表達式的所有符合項目替換為指定字串。 |


### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)