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

| Egenskap | Beskrivning |
| :- | :- |
| [`paragraphs`](/slides/python-net/sv/aspose.slides/itextframe/paragraphs/) | Returnerar listan med alla stycken i en ram.<br/>            Skrivskyddad [`IParagraphCollection`](/slides/python-net/sv/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/sv/aspose.slides/itextframe/text/) | Hämtar eller anger den rena texten för en TextFrame.<br/>            Läs-skriv **str**. |
| [`text_frame_format`](/slides/python-net/sv/aspose.slides/itextframe/text_frame_format/) | Returnerar formateringsobjektet för detta TextFrame-objekt.<br/>            Skrivskyddad [`ITextFrameFormat`](/slides/python-net/sv/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/itextframe/hyperlink_queries/) | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar.<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/sv/aspose.slides/itextframe/parent_shape/) | Returnerar den överordnade formen eller None om föräldraobjektet inte implementerar IShape-gränssnittet<br/>            Skrivskyddad [`IShape`](/slides/python-net/sv/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/sv/aspose.slides/itextframe/parent_cell/) | Returnerar den överordnade cellen eller None om föräldraobjektet inte implementerar ICell-gränssnittet.<br/>            Skrivskyddad [`ICell`](/slides/python-net/sv/aspose.slides/icell). |
| [`slide`](/slides/python-net/sv/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/itextframe/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Markerar alla matchningar av provtexten med angiven färg. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Markerar alla matchningar av provtexten med angiven färg. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Markerar alla matchningar av provtexten med angiven färg. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Markerar alla matchningar av reguljära uttrycket med angiven färg. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Markerar alla matchningar av reguljära uttrycket med angiven färg. |
| [`get_text_rect(self)`](/slides/python-net/sv/aspose.slides/itextframe/get_text_rect/#) | Hämtar textrutan som definieras av geometrin för den överordnade formen. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Sammanfogar körningar med samma formatering i alla stycken. |
| [`split_text_by_columns(self)`](/slides/python-net/sv/aspose.slides/itextframe/split_text_by_columns/#) | Delar upp textinnehållet i [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe) i en array av strängar,  <br/>            där varje element motsvarar en separat textkolumn inom ramen. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/sv/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/sv/aspose.slides/itextframe/replace_regex/#str-str) | Ersätter alla matchningar av reguljärt uttryck med den angivna strängen. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)