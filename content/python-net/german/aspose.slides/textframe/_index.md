---
title: TextFrame class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/textframe/
---
## TextFrame Klasse

Stellt ein TextFrame dar.

Der TextFrame-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`paragraphs`](/slides/python-net/de/aspose.slides/textframe/paragraphs/) | Returns the list of all paragraphs in a frame.<br/>            Nur lesbar [`IParagraphCollection`](/slides/python-net/de/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/de/aspose.slides/textframe/text/) | Gets or sets the plain text for a TextFrame.<br/>            Lese/Schreib **str**. |
| [`text_frame_format`](/slides/python-net/de/aspose.slides/textframe/text_frame_format/) | Returns the formatting object for this TextFrame object.<br/>            Nur lesbar [`ITextFrameFormat`](/slides/python-net/de/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/textframe/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Nur lesbar [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/de/aspose.slides/textframe/slide/) | Returns the parent slide of a TextFrame.<br/>            Nur lesbar [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/textframe/presentation/) | Returns the parent presentation of a TextFrame.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/de/aspose.slides/textframe/parent_shape/) | Returns the parent shape or None if the parent object does not implement the IShape interface<br/>            Nur lesbar [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/de/aspose.slides/textframe/parent_cell/) | Returns the parent cell or None if the parent object does not implement the ICell interface.<br/>            Nur lesbar [`ICell`](/slides/python-net/de/aspose.slides/icell). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/de/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/de/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/de/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Highlights all matches of the sample text with the specified color. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/de/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Highlights all matches of the regular expression with the specified color. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/de/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Highlights all matches of the regular expression with the specified color. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/textframe/join_portions_with_same_formatting/#) | Verbindet Runs mit gleicher Formatierung in allen Absätzen. |
| [`split_text_by_columns(self)`](/slides/python-net/de/aspose.slides/textframe/split_text_by_columns/#) | Splits the text content of the [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe) into an array of strings,  <br/>            where each element corresponds to a separate text column within the frame. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/de/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Replaces all occurrences of the specified text with another specified text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/de/aspose.slides/textframe/replace_regex/#str-str) | Replaces all matches of regular expression with specified string. |
| [`get_text_rect(self)`](/slides/python-net/de/aspose.slides/textframe/get_text_rect/#) | Gets the text rectangle defined by the geometry of the parent shape. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)