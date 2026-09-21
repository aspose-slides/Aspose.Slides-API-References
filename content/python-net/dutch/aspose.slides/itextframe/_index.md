---
title: ITextFrame class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/itextframe/
---
## ITextFrame klasse

Represents a TextFrame.

The ITextFrame type exposes the following members:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`paragraphs`](/slides/python-net/nl/aspose.slides/itextframe/paragraphs/) | Geeft de lijst van alle alinea's in een kader terug.<br/>            Alleen-lezen [`IParagraphCollection`](/slides/python-net/nl/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/nl/aspose.slides/itextframe/text/) | Leest of stelt de platte tekst voor een TextFrame in.<br/>            Lezen/Schrijven **str**. |
| [`text_frame_format`](/slides/python-net/nl/aspose.slides/itextframe/text_frame_format/) | Geeft het opmaakobject voor dit TextFrame-object terug.<br/>            Alleen-lezen [`ITextFrameFormat`](/slides/python-net/nl/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/itextframe/hyperlink_queries/) | Biedt gemakkelijke toegang tot opgenomen hyperlinks.<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/nl/aspose.slides/itextframe/parent_shape/) | Geeft de bovenliggende vorm terug of None als het bovenliggende object de IShape-interface niet implementeert<br/>            Alleen-lezen [`IShape`](/slides/python-net/nl/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/nl/aspose.slides/itextframe/parent_cell/) | Geeft de bovenliggende cel terug of None als het bovenliggende object de ICell-interface niet implementeert.<br/>            Alleen-lezen [`ICell`](/slides/python-net/nl/aspose.slides/icell). |
| [`slide`](/slides/python-net/nl/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/itextframe/presentation/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/nl/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/nl/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/nl/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/nl/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/nl/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Voegt runs met dezelfde opmaak samen in alle alinea's. |
| [`split_text_by_columns(self)`](/slides/python-net/nl/aspose.slides/itextframe/split_text_by_columns/#) | Splitst de tekstinhoud van de [`ITextFrame`](/slides/python-net/nl/aspose.slides/itextframe) in een array van strings,<br/>            waarbij elk element overeenkomt met een aparte tekstkolom binnen het kader. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/nl/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/nl/aspose.slides/itextframe/replace_regex/#str-str) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)