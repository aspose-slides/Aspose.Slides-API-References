---
title: ITextFrame class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/itextframe/
---
## ITextFrame 类

Represents a TextFrame.

The ITextFrame type exposes the following members:

## 属性

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/zh/aspose.slides/itextframe/paragraphs/) | Returns the list of all paragraphs in a frame.<br/>            只读 [`IParagraphCollection`](/slides/python-net/zh/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/zh/aspose.slides/itextframe/text/) | Gets or sets the plain text for a TextFrame.<br/>            读写 **str**. |
| [`text_frame_format`](/slides/python-net/zh/aspose.slides/itextframe/text_frame_format/) | Returns the formatting object for this TextFrame object.<br/>            只读 [`ITextFrameFormat`](/slides/python-net/zh/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/itextframe/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/zh/aspose.slides/itextframe/parent_shape/) | Returns the parent shape or None if the parent object does not implement the IShape interface<br/>            只读 [`IShape`](/slides/python-net/zh/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/zh/aspose.slides/itextframe/parent_cell/) | Returns the parent cell or None if the parent object does not implement the ICell interface.<br/>            只读 [`ICell`](/slides/python-net/zh/aspose.slides/icell). |
| [`slide`](/slides/python-net/zh/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/itextframe/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | 使用指定的颜色突出显示所有样本文本的匹配项。 |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/zh/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | 使用指定的颜色突出显示所有样本文本的匹配项。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | 使用指定的颜色突出显示所有样本文本的匹配项。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | 使用指定的颜色突出显示正则表达式的所有匹配项。 |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/zh/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | 使用指定的颜色突出显示正则表达式的所有匹配项。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/itextframe/join_portions_with_same_formatting/#) | 在所有段落中合并具有相同格式的运行。 |
| [`split_text_by_columns(self)`](/slides/python-net/zh/aspose.slides/itextframe/split_text_by_columns/#) | 将 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe) 的文本内容拆分为字符串数组，<br/>            每个元素对应帧内的单独文本列。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 将指定文本的所有出现替换为另一个指定文本。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh/aspose.slides/itextframe/replace_regex/#str-str) | 将正则表达式的所有匹配替换为指定的字符串。 |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)