---
title: TextFrame class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/textframe/
---
## TextFrame klasse

Stelt een TextFrame voor.

Het TextFrame-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`paragraphs`](/slides/python-net/nl/aspose.slides/textframe/paragraphs/) | Retourneert de lijst van alle alinea's in een frame.<br/>            Alleen-lezen [`IParagraphCollection`](/slides/python-net/nl/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/nl/aspose.slides/textframe/text/) | Haalt of stelt de platte tekst voor een TextFrame in.<br/>            Lezen/Schrijven **str**. |
| [`text_frame_format`](/slides/python-net/nl/aspose.slides/textframe/text_frame_format/) | Retourneert het opmaakobject voor dit TextFrame-object.<br/>            Alleen-lezen [`ITextFrameFormat`](/slides/python-net/nl/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/textframe/hyperlink_queries/) | Biedt eenvoudige toegang tot de contained hyperlinks.<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/nl/aspose.slides/textframe/slide/) | Retourneert de bovenliggende slide van een TextFrame.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/textframe/presentation/) | Retourneert de bovenliggende presentatie van een TextFrame.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/nl/aspose.slides/textframe/parent_shape/) | Retourneert de bovenliggende shape of None als het bovenliggende object de IShape-interface niet implementeert<br/>            Alleen-lezen [`IShape`](/slides/python-net/nl/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/nl/aspose.slides/textframe/parent_cell/) | Retourneert de bovenliggende cell of None als het bovenliggende object de ICell-interface niet implementeert.<br/>            Alleen-lezen [`ICell`](/slides/python-net/nl/aspose.slides/icell). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/nl/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/nl/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/nl/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/nl/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/nl/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/textframe/join_portions_with_same_formatting/#) | Voegt runs samen met dezelfde opmaak in alle alinea's. |
| [`split_text_by_columns(self)`](/slides/python-net/nl/aspose.slides/textframe/split_text_by_columns/#) | Splitst de tekstinhoud van de [`ITextFrame`](/slides/python-net/nl/aspose.slides/itextframe) in een array van strings, <br/>            waarbij elk element overeenkomt met een aparte tekstkolom binnen het frame. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/nl/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/nl/aspose.slides/textframe/replace_regex/#str-str) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)