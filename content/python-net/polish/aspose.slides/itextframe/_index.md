---
title: ITextFrame class
second_title: Aspose.Slides dla Pythona przez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/itextframe/
---
## ITextFrame klasa

Reprezentuje TextFrame.

Typ ITextFrame udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`paragraphs`](/slides/python-net/pl/aspose.slides/itextframe/paragraphs/) | Zwraca listę wszystkich akapitów w ramce.<br/>            Tylko do odczytu [`IParagraphCollection`](/slides/python-net/pl/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/pl/aspose.slides/itextframe/text/) | Pobiera lub ustawia zwykły tekst dla TextFrame.<br/>            Odczyt/zapis **str**. |
| [`text_frame_format`](/slides/python-net/pl/aspose.slides/itextframe/text_frame_format/) | Zwraca obiekt formatowania dla tego obiektu TextFrame.<br/>            Tylko do odczytu [`ITextFrameFormat`](/slides/python-net/pl/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/itextframe/hyperlink_queries/) | Umożliwia łatwy dostęp do zawartych odnośników hipertekstowych.<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/pl/aspose.slides/itextframe/parent_shape/) | Zwraca nadrzędny kształt lub None, jeśli obiekt nadrzędny nie implementuje interfejsu IShape<br/>            Tylko do odczytu [`IShape`](/slides/python-net/pl/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/pl/aspose.slides/itextframe/parent_cell/) | Zwraca nadrzędną komórkę lub None, jeśli obiekt nadrzędny nie implementuje interfejsu ICell.<br/>            Tylko do odczytu [`ICell`](/slides/python-net/pl/aspose.slides/icell). |
| [`slide`](/slides/python-net/pl/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/itextframe/presentation/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/pl/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Podświetla wszystkie dopasowania przykładowego tekstu przy użyciu określonego koloru. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/pl/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Podświetla wszystkie dopasowania przykładowego tekstu przy użyciu określonego koloru. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/pl/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Podświetla wszystkie dopasowania przykładowego tekstu przy użyciu określonego koloru. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/pl/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Podświetla wszystkie dopasowania wyrażenia regularnego przy użyciu określonego koloru. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/pl/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Podświetla wszystkie dopasowania wyrażenia regularnego przy użyciu określonego koloru. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Łączy ciągi o tym samym formatowaniu we wszystkich akapitach. |
| [`split_text_by_columns(self)`](/slides/python-net/pl/aspose.slides/itextframe/split_text_by_columns/#) | Dzieli zawartość tekstową [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe) na tablicę stringów, <br/>            gdzie każdy element odpowiada osobnej kolumnie tekstowej w ramce. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/pl/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/pl/aspose.slides/itextframe/replace_regex/#str-str) | Zastępuje wszystkie dopasowania wyrażenia regularnego określonym ciągiem znaków. |


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)