---
title: ITextFrame class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/itextframe/
---
## ITextFrame Klasse

Stellt einen TextFrame dar.

Der ITextFrame-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`paragraphs`](/slides/python-net/de/aspose.slides/itextframe/paragraphs/) | Gibt die Liste aller Absätze in einem Rahmen zurück.<br/>            Nur lesbar [`IParagraphCollection`](/slides/python-net/de/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/de/aspose.slides/itextframe/text/) | Liest oder setzt den Klartext für einen TextFrame.<br/>            Lese/Schreib **str**. |
| [`text_frame_format`](/slides/python-net/de/aspose.slides/itextframe/text_frame_format/) | Gibt das Formatierungsobjekt für dieses TextFrame-Objekt zurück.<br/>            Nur lesbar [`ITextFrameFormat`](/slides/python-net/de/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/itextframe/hyperlink_queries/) | Bietet einfachen Zugriff auf enthaltene Hyperlinks.<br/>            Nur lesbar [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/de/aspose.slides/itextframe/parent_shape/) | Gibt die übergeordnete Form zurück oder None, wenn das übergeordnete Objekt das IShape-Interface nicht implementiert<br/>            Nur lesbar [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/de/aspose.slides/itextframe/parent_cell/) | Gibt die übergeordnete Zelle zurück oder None, wenn das übergeordnete Objekt das ICell-Interface nicht implementiert.<br/>            Nur lesbar [`ICell`](/slides/python-net/de/aspose.slides/icell). |
| [`slide`](/slides/python-net/de/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/itextframe/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/de/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Hebt alle Vorkommen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/de/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Hebt alle Vorkommen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/de/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Hebt alle Vorkommen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/de/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/de/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Verbindet Laufblöcke mit derselben Formatierung in allen Absätzen. |
| [`split_text_by_columns(self)`](/slides/python-net/de/aspose.slides/itextframe/split_text_by_columns/#) | Teilt den Textinhalt von [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe) in ein Array von Zeichenketten,  <br/>            wobei jedes Element einer separaten Textspalte innerhalb des Rahmens entspricht. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/de/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/de/aspose.slides/itextframe/replace_regex/#str-str) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch die angegebene Zeichenkette. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)