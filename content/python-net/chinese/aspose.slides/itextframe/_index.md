---
title: ITextFrame class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/itextframe/
---
## ITextFrame 类

表示一个 TextFrame。

ITextFrame 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/zh/aspose.slides/itextframe/paragraphs/) | 返回帧中所有段落的列表。<br/>            只读 [`IParagraphCollection`](/slides/python-net/zh/aspose.slides/iparagraphcollection)。 |
| [`text`](/slides/python-net/zh/aspose.slides/itextframe/text/) | 获取或设置 TextFrame 的纯文本。<br/>            可读写 **str**。 |
| [`text_frame_format`](/slides/python-net/zh/aspose.slides/itextframe/text_frame_format/) | 返回此 TextFrame 对象的格式化对象。<br/>            只读 [`ITextFrameFormat`](/slides/python-net/zh/aspose.slides/itextframeformat)。 |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/itextframe/hyperlink_queries/) | 提供对包含的超链接的便捷访问。<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries)。 |
| [`parent_shape`](/slides/python-net/zh/aspose.slides/itextframe/parent_shape/) | 返回父形状，如果父对象未实现 IShape 接口则返回 None。<br/>            只读 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |
| [`parent_cell`](/slides/python-net/zh/aspose.slides/itextframe/parent_cell/) | 返回父单元格，如果父对象未实现 ICell 接口则返回 None。<br/>            只读 [`ICell`](/slides/python-net/zh/aspose.slides/icell)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/itextframe/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | 使用指定颜色突出显示示例文本的所有匹配项。 |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/zh/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | 使用指定颜色突出显示示例文本的所有匹配项。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | 使用指定颜色突出显示示例文本的所有匹配项。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/zh/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/itextframe/join_portions_with_same_formatting/#) | 在所有段落中合并具有相同格式的运行。 |
| [`split_text_by_columns(self)`](/slides/python-net/zh/aspose.slides/itextframe/split_text_by_columns/#) | 将 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe) 的文本内容拆分为字符串数组，<br/>            每个元素对应帧内的单独文本列。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 将指定文本的所有出现替换为另一个指定文本。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh/aspose.slides/itextframe/replace_regex/#str-str) | 将正则表达式的所有匹配项替换为指定字符串。 |


### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)