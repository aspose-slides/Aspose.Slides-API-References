---
title: ITextFrame class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/itextframe/
---
## ITextFrame klasse

Stelt een TextFrame voor.

Het ITextFrame-type toont de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`paragraphs`](/slides/python-net/nl/aspose.slides/itextframe/paragraphs/) | Retourneert de lijst van alle alinea's in een frame.<br/>            Alleen-lezen [`IParagraphCollection`](/slides/python-net/nl/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/nl/aspose.slides/itextframe/text/) | Haalt op of stelt de platte tekst voor een TextFrame in.<br/>            Lezen/schrijven **str**. |
| [`text_frame_format`](/slides/python-net/nl/aspose.slides/itextframe/text_frame_format/) | Retourneert het opmaakobject voor dit TextFrame-object.<br/>            Alleen-lezen [`ITextFrameFormat`](/slides/python-net/nl/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/itextframe/hyperlink_queries/) | Biedt gemakkelijke toegang tot ingesloten hyperlinks.<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/nl/aspose.slides/itextframe/parent_shape/) | Retourneert de bovenliggende vorm of None als het bovenliggende object de IShape-interface niet implementeert<br/>            Alleen-lezen [`IShape`](/slides/python-net/nl/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/nl/aspose.slides/itextframe/parent_cell/) | Retourneert de bovenliggende cel of None als het bovenliggende object de ICell-interface niet implementeert.<br/>            Alleen-lezen [`ICell`](/slides/python-net/nl/aspose.slides/icell). |
| [`slide`](/slides/python-net/nl/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/itextframe/presentation/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/nl/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/nl/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/nl/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/nl/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/nl/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Voegt runs samen met dezelfde opmaak in alle alinea's. |
| [`split_text_by_columns(self)`](/slides/python-net/nl/aspose.slides/itextframe/split_text_by_columns/#) | Splitst de tekstinhoud van de [`ITextFrame`](/slides/python-net/nl/aspose.slides/itextframe) in een array van strings,<br/>            waarbij elk element overeenkomt met een afzonderlijke tekstkolom binnen het frame. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/nl/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/nl/aspose.slides/itextframe/replace_regex/#str-str) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)