---
title: ITextFrame class
second_title: Aspose.Slides pro Python prostřednictvím .NET API reference
description: 
type: docs
url: /cs/aspose.slides/itextframe/
---
## ITextFrame třída

Představuje TextFrame.

Typ ITextFrame poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`paragraphs`](/slides/python-net/cs/aspose.slides/itextframe/paragraphs/) | Vrací seznam všech odstavců v rámečku.<br/>            Pouze pro čtení [`IParagraphCollection`](/slides/python-net/cs/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/cs/aspose.slides/itextframe/text/) | Získá nebo nastaví prostý text pro TextFrame.<br/>            Čtení/zápis **str**. |
| [`text_frame_format`](/slides/python-net/cs/aspose.slides/itextframe/text_frame_format/) | Vrací objekt formátování pro tento objekt TextFrame.<br/>            Pouze pro čtení [`ITextFrameFormat`](/slides/python-net/cs/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/itextframe/hyperlink_queries/) | Poskytuje snadný přístup k obsaženým hypertextovým odkazům.<br/>            Pouze pro čtení [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/cs/aspose.slides/itextframe/parent_shape/) | Vrací nadřazený tvar nebo None, pokud nadřazený objekt neimplementuje rozhraní IShape<br/>            Pouze pro čtení [`IShape`](/slides/python-net/cs/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/cs/aspose.slides/itextframe/parent_cell/) | Vrací nadřazenou buňku nebo None, pokud nadřazený objekt neimplementuje rozhraní ICell.<br/>            Pouze pro čtení [`ICell`](/slides/python-net/cs/aspose.slides/icell). |
| [`slide`](/slides/python-net/cs/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/itextframe/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/cs/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Zvýrazní všechny výskyty vzorového textu zadanou barvou. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/cs/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Zvýrazní všechny výskyty vzorového textu zadanou barvou. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/cs/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Zvýrazní všechny výskyty vzorového textu zadanou barvou. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/cs/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Zvýrazní všechny výskyty regulárního výrazu zadanou barvou. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/cs/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Zvýrazní všechny výskyty regulárního výrazu zadanou barvou. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Spojí úseky se stejným formátováním ve všech odstavcích. |
| [`split_text_by_columns(self)`](/slides/python-net/cs/aspose.slides/itextframe/split_text_by_columns/#) | Rozdělí textový obsah [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe) do pole řetězců,  <br/>            kde každý prvek odpovídá samostatnému sloupci textu v rámci rámce. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/cs/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Nahradí všechny výskyty zadaného textu jiným zadaným textem. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/cs/aspose.slides/itextframe/replace_regex/#str-str) | Nahradí všechny výskyty regulárního výrazu zadaným řetězcem. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)