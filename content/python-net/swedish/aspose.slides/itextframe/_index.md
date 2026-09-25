---
title: ITextFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/itextframe/
---
## ITextFrame klass

Representerar en TextFrame.

Typen ITextFrame exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/sv/aspose.slides/itextframe/paragraphs/) | Returnerar listan över alla stycken i en ram.<br/>            Endast läsning [`IParagraphCollection`](/slides/python-net/sv/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/sv/aspose.slides/itextframe/text/) | Hämtar eller anger vanlig text för en TextFrame.<br/>            Läs/skriv **str**. |
| [`text_frame_format`](/slides/python-net/sv/aspose.slides/itextframe/text_frame_format/) | Returnerar formateringsobjektet för detta TextFrame-objekt.<br/>            Endast läsning [`ITextFrameFormat`](/slides/python-net/sv/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/itextframe/hyperlink_queries/) | Tillhandahåller enklare åtkomst till inbäddade hyperlänkar.<br/>            Endast läsning [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/sv/aspose.slides/itextframe/parent_shape/) | Returnerar den överordnade formen eller None om det överordnade objektet inte implementerar IShape-gränssnittet<br/>            Endast läsning [`IShape`](/slides/python-net/sv/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/sv/aspose.slides/itextframe/parent_cell/) | Returnerar den överordnade cellen eller None om det överordnade objektet inte implementerar ICell-gränssnittet.<br/>            Endast läsning [`ICell`](/slides/python-net/sv/aspose.slides/icell). |
| [`slide`](/slides/python-net/sv/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/itextframe/presentation/) |  |

## Metoder

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Markerar alla matchningar av reguljärt uttryck med den angivna färgen. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Markerar alla matchningar av reguljärt uttryck med den angivna färgen. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Sammanfogar körningar med samma formatering i alla stycken. |
| [`split_text_by_columns(self)`](/slides/python-net/sv/aspose.slides/itextframe/split_text_by_columns/#) | Delar upp textinnehållet i [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe) i en array av strängar,  <br/>            där varje element motsvarar en separat textkolumn i ramen. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/sv/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/sv/aspose.slides/itextframe/replace_regex/#str-str) | Ersätter alla matchningar av reguljärt uttryck med angiven sträng. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)