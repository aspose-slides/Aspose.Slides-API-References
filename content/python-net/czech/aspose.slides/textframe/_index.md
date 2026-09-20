---
title: TextFrame class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/textframe/
---
## TextFrame třída

Represents a TextFrame.

The TextFrame type exposes the following members:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/cs/aspose.slides/textframe/paragraphs/) | Returns the list of all paragraphs in a frame.<br/>            Read-only [`IParagraphCollection`](/slides/python-net/cs/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/cs/aspose.slides/textframe/text/) | Gets or sets the plain text for a TextFrame.<br/>            Read/write **str**. |
| [`text_frame_format`](/slides/python-net/cs/aspose.slides/textframe/text_frame_format/) | Returns the formatting object for this TextFrame object.<br/>            Read-only [`ITextFrameFormat`](/slides/python-net/cs/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/textframe/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/cs/aspose.slides/textframe/slide/) | Returns the parent slide of a TextFrame.<br/>            Read-only [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/textframe/presentation/) | Returns the parent presentation of a TextFrame.<br/>            Read-only [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/cs/aspose.slides/textframe/parent_shape/) | Returns the parent shape or None if the parent object does not implement the IShape interface<br/>            Read-only [`IShape`](/slides/python-net/cs/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/cs/aspose.slides/textframe/parent_cell/) | Returns the parent cell or None if the parent object does not implement the ICell interface.<br/>            Read-only [`ICell`](/slides/python-net/cs/aspose.slides/icell). |

## Metody

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/cs/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/cs/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/cs/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Highlights all matches of the sample text with the specified color. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/cs/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Highlights all matches of the regular expression with the specified color. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/cs/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | Highlights all matches of the regular expression with the specified color. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/textframe/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs. |
| [`split_text_by_columns(self)`](/slides/python-net/cs/aspose.slides/textframe/split_text_by_columns/#) | Splits the text content of the [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe) into an array of strings,  <br/>            where each element corresponds to a separate text column within the frame. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/cs/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Replaces all occurrences of the specified text with another specified text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/cs/aspose.slides/textframe/replace_regex/#str-str) | Replaces all matches of regular expression with specified string. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)