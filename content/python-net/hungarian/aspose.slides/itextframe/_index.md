---
title: ITextFrame class
second_title: Aspose.Slides a Pythonhoz a .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/itextframe/
---
## ITextFrame osztály

Egy TextFrame-et képvisel.

Az ITextFrame típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`paragraphs`](/slides/python-net/hu/aspose.slides/itextframe/paragraphs/) | Returns the list of all paragraphs in a frame.<br/>            Read-only [`IParagraphCollection`](/slides/python-net/hu/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/hu/aspose.slides/itextframe/text/) | Gets or sets the plain text for a TextFrame.<br/>            Read/write **str**. |
| [`text_frame_format`](/slides/python-net/hu/aspose.slides/itextframe/text_frame_format/) | Returns the formatting object for this TextFrame object.<br/>            Read-only [`ITextFrameFormat`](/slides/python-net/hu/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/itextframe/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/hu/aspose.slides/itextframe/parent_shape/) | Returns the parent shape or None if the parent object does not implement the IShape interface<br/>            Read-only [`IShape`](/slides/python-net/hu/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/hu/aspose.slides/itextframe/parent_cell/) | Returns the parent cell or None if the parent object does not implement the ICell interface.<br/>            Read-only [`ICell`](/slides/python-net/hu/aspose.slides/icell). |
| [`slide`](/slides/python-net/hu/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/itextframe/presentation/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hu/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/hu/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hu/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Highlights all matches of the sample text with the specified color. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hu/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Highlights all matches of the regular expression with the specified color. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/hu/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Highlights all matches of the regular expression with the specified color. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs. |
| [`split_text_by_columns(self)`](/slides/python-net/hu/aspose.slides/itextframe/split_text_by_columns/#) | Splits the text content of the [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe) into an array of strings,  <br/>            where each element corresponds to a separate text column within the frame. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hu/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Replaces all occurrences of the specified text with another specified text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hu/aspose.slides/itextframe/replace_regex/#str-str) | Replaces all matches of regular expression with specified string. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)