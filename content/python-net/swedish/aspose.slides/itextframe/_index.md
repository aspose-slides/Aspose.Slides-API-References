---
title: ITextFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/itextframe/
---
## ITextFrame klass

Represents a TextFrame.

The ITextFrame type exposes the following members:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`paragraphs`](/slides/python-net/sv/aspose.slides/itextframe/paragraphs/) | Returnerar listan över alla stycken i en ram.<br/>            Skrivskyddad [`IParagraphCollection`](/slides/python-net/sv/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/sv/aspose.slides/itextframe/text/) | Hämtar eller anger oformaterad text för en TextFrame.<br/>            Läs/skriv **str**. |
| [`text_frame_format`](/slides/python-net/sv/aspose.slides/itextframe/text_frame_format/) | Returnerar formateringsobjektet för detta TextFrame-objekt.<br/>            Skrivskyddad [`ITextFrameFormat`](/slides/python-net/sv/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/itextframe/hyperlink_queries/) | Tillhandahåller enkel åtkomst till innehållna hyperlänkar.<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/sv/aspose.slides/itextframe/parent_shape/) | Returnerar föräldraformen eller None om föräldraobjektet inte implementerar IShape-gränssnittet<br/>            Skrivskyddad [`IShape`](/slides/python-net/sv/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/sv/aspose.slides/itextframe/parent_cell/) | Returnerar föräldracellen eller None om föräldraobjektet inte implementerar ICell-gränssnittet.<br/>            Skrivskyddad [`ICell`](/slides/python-net/sv/aspose.slides/icell). |
| [`slide`](/slides/python-net/sv/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/itextframe/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Markerar alla träffar av reguljärt uttrycket med den angivna färgen. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/sv/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Markerar alla träffar av reguljärt uttrycket med den angivna färgen. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Sammanfogar löp med samma formatering i alla stycken. |
| [`split_text_by_columns(self)`](/slides/python-net/sv/aspose.slides/itextframe/split_text_by_columns/#) | Delar upp textinnehållet i [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe) i en array av strängar, <br/>            där varje element motsvarar en separat textkolumn i ramen. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/sv/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/sv/aspose.slides/itextframe/replace_regex/#str-str) | Ersätter alla träffar av reguljärt uttryck med angiven sträng. |

### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)