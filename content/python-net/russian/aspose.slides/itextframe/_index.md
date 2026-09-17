---
title: ITextFrame class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/itextframe/
---
## ITextFrame класс

Represents a TextFrame.

The ITextFrame type exposes the following members:

## Свойства

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/ru/aspose.slides/itextframe/paragraphs/) | Returns the list of all paragraphs in a frame.<br/>            Только для чтения [`IParagraphCollection`](/slides/python-net/ru/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ru/aspose.slides/itextframe/text/) | Gets or sets the plain text for a TextFrame.<br/>            Чтение/запись **str**. |
| [`text_frame_format`](/slides/python-net/ru/aspose.slides/itextframe/text_frame_format/) | Returns the formatting object for this TextFrame object.<br/>            Только для чтения [`ITextFrameFormat`](/slides/python-net/ru/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/itextframe/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/ru/aspose.slides/itextframe/parent_shape/) | Returns the parent shape or None if the parent object does not implement the IShape interface<br/>            Только для чтения [`IShape`](/slides/python-net/ru/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ru/aspose.slides/itextframe/parent_cell/) | Returns the parent cell or None if the parent object does not implement the ICell interface.<br/>            Только для чтения [`ICell`](/slides/python-net/ru/aspose.slides/icell). |
| [`slide`](/slides/python-net/ru/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/itextframe/presentation/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ru/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ru/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ru/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Highlights all matches of the sample text with the specified color. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ru/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Highlights all matches of the regular expression with the specified color. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ru/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Highlights all matches of the regular expression with the specified color. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs. |
| [`split_text_by_columns(self)`](/slides/python-net/ru/aspose.slides/itextframe/split_text_by_columns/#) | Splits the text content of the [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe) into an array of strings,  <br/>            where each element corresponds to a separate text column within the frame. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ru/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Replaces all occurrences of the specified text with another specified text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ru/aspose.slides/itextframe/replace_regex/#str-str) | Replaces all matches of regular expression with specified string. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)