---
title: ITextFrame class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/itextframe/
---
## ITextFrame Klasse

Stellt einen TextFrame dar.

Der Typ ITextFrame stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`paragraphs`](/slides/python-net/de/aspose.slides/itextframe/paragraphs/) | Gibt die Liste aller Absätze in einem Rahmen zurück.<br/>            Nur-Lesen [`IParagraphCollection`](/slides/python-net/de/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/de/aspose.slides/itextframe/text/) | Liest oder setzt den einfachen Text für einen TextFrame.<br/>            Lese-/Schreibbar **str**. |
| [`text_frame_format`](/slides/python-net/de/aspose.slides/itextframe/text_frame_format/) | Gibt das Formatierungsobjekt für dieses TextFrame-Objekt zurück.<br/>            Nur-Lesen [`ITextFrameFormat`](/slides/python-net/de/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/itextframe/hyperlink_queries/) | Ermöglicht einfachen Zugriff auf enthaltene Hyperlinks.<br/>            Nur-Lesen [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/de/aspose.slides/itextframe/parent_shape/) | Gibt das übergeordnete Shape zurück oder None, wenn das übergeordnete Objekt das IShape-Interface nicht implementiert<br/>            Nur-Lesen [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/de/aspose.slides/itextframe/parent_cell/) | Gibt die übergeordnete Zelle zurück oder None, wenn das übergeordnete Objekt das ICell-Interface nicht implementiert.<br/>            Nur-Lesen [`ICell`](/slides/python-net/de/aspose.slides/icell). |
| [`slide`](/slides/python-net/de/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/itextframe/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/de/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Hebt alle Übereinstimmungen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/de/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Hebt alle Übereinstimmungen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/de/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Hebt alle Übereinstimmungen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/de/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/de/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Verbindet Durchläufe mit gleicher Formatierung in allen Absätzen. |
| [`split_text_by_columns(self)`](/slides/python-net/de/aspose.slides/itextframe/split_text_by_columns/#) | Teilt den Textinhalt des [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe) in ein Array von Zeichenketten,  <br/>            wobei jedes Element einer separaten Textspalte innerhalb des Rahmens entspricht. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/de/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/de/aspose.slides/itextframe/replace_regex/#str-str) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch die angegebene Zeichenkette. |

### Siehe Auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)