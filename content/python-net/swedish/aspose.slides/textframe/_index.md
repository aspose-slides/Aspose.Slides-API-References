---
title: TextFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/textframe/
---
## TextFrame klass

Representerar en TextFrame.

TextFrame-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`paragraphs`](/slides/python-net/sv/aspose.slides/textframe/paragraphs/) | Returnerar listan över alla stycken i en ram.<br/>            Skrivskyddad [`IParagraphCollection`](/slides/python-net/sv/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/sv/aspose.slides/textframe/text/) | Hämtar eller anger vanlig text för en TextFrame.<br/>            Läs/skriv **str**. |
| [`text_frame_format`](/slides/python-net/sv/aspose.slides/textframe/text_frame_format/) | Returnerar formateringsobjektet för detta TextFrame-objekt.<br/>            Skrivskyddad [`ITextFrameFormat`](/slides/python-net/sv/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/textframe/hyperlink_queries/) | Ger enkel åtkomst till innehållna hyperlänkar.<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/sv/aspose.slides/textframe/slide/) | Returnerar föräldra-bilden för en TextFrame.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/textframe/presentation/) | Returnerar föräldrapresentationen för en TextFrame.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/sv/aspose.slides/textframe/parent_shape/) | Returnerar den överordnade formen eller None om det överordnade objektet inte implementerar IShape-gränssnittet<br/>            Skrivskyddad [`IShape`](/slides/python-net/sv/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/sv/aspose.slides/textframe/parent_cell/) | Returnerar den överordnade cellen eller None om det överordnade objektet inte implementerar ICell-gränssnittet.<br/>            Skrivskyddad [`ICell`](/slides/python-net/sv/aspose.slides/icell). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/sv/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/sv/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/sv/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/sv/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Markerar alla matchningar av det reguljära uttrycket med den angivna färgen. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/sv/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Markerar alla matchningar av det reguljära uttrycket med den angivna färgen. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/textframe/join_portions_with_same_formatting/#) | Sammanfogar körningar med samma formatering i alla stycken. |
| [`split_text_by_columns(self)`](/slides/python-net/sv/aspose.slides/textframe/split_text_by_columns/#) | Delar upp textinnehållet i [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe) i en array av strängar, <br/>            där varje element motsvarar en separat textkolumn i ramen. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/sv/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/sv/aspose.slides/textframe/replace_regex/#str-str) | Ersätter alla matchningar av reguljärt uttryck med angiven sträng. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)