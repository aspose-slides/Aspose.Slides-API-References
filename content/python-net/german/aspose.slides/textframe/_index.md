---
title: TextFrame class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/textframe/
---
## TextFrame Klasse

Stellt ein TextFrame dar.

Der TextFrame-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`paragraphs`](/slides/python-net/de/aspose.slides/textframe/paragraphs/) | Gibt die Liste aller Absätze in einem Rahmen zurück.<br/>            Nur lesen [`IParagraphCollection`](/slides/python-net/de/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/de/aspose.slides/textframe/text/) | Liest oder schreibt den Klartext für ein TextFrame.<br/>            Lese/Schreib **str**. |
| [`text_frame_format`](/slides/python-net/de/aspose.slides/textframe/text_frame_format/) | Gibt das Formatierungsobjekt für dieses TextFrame-Objekt zurück.<br/>            Nur lesen [`ITextFrameFormat`](/slides/python-net/de/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/textframe/hyperlink_queries/) | Bietet einfachen Zugriff auf enthaltene Hyperlinks.<br/>            Nur lesen [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/de/aspose.slides/textframe/slide/) | Gibt die übergeordnete Folie eines TextFrames zurück.<br/>            Nur lesen [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/textframe/presentation/) | Gibt die übergeordnete Präsentation eines TextFrames zurück.<br/>            Nur lesen [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/de/aspose.slides/textframe/parent_shape/) | Gibt die übergeordnete Form zurück oder None, wenn das übergeordnete Objekt das IShape-Interface nicht implementiert<br/>            Nur lesen [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/de/aspose.slides/textframe/parent_cell/) | Gibt die übergeordnete Zelle zurück oder None, wenn das übergeordnete Objekt das ICell-Interface nicht implementiert.<br/>            Nur lesen [`ICell`](/slides/python-net/de/aspose.slides/icell). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/de/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Hebt alle Übereinstimmungen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/de/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Hebt alle Übereinstimmungen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/de/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Hebt alle Übereinstimmungen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/de/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/de/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/textframe/join_portions_with_same_formatting/#) | Verbindet Runs mit gleicher Formatierung in allen Absätzen. |
| [`split_text_by_columns(self)`](/slides/python-net/de/aspose.slides/textframe/split_text_by_columns/#) | Teilt den Textinhalt von [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe) in ein Array von Zeichenketten,  <br/>            wobei jedes Element einer separaten Textspalte innerhalb des Rahmens entspricht. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/de/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/de/aspose.slides/textframe/replace_regex/#str-str) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch die angegebene Zeichenkette. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)