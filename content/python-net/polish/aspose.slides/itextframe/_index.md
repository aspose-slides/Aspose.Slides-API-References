---
title: ITextFrame class
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/itextframe/
---
## ITextFrame klasa

Represents a TextFrame.

The ITextFrame type exposes the following members:

## Właściwości

| Property | Opis |
| :- | :- |
| [`paragraphs`](/slides/python-net/pl/aspose.slides/itextframe/paragraphs/) | Zwraca listę wszystkich paragrafów w ramce.<br/>            Tylko do odczytu [`IParagraphCollection`](/slides/python-net/pl/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/pl/aspose.slides/itextframe/text/) | Pobiera lub ustawia zwykły tekst dla TextFrame.<br/>            Odczyt/zapis **str**. |
| [`text_frame_format`](/slides/python-net/pl/aspose.slides/itextframe/text_frame_format/) | Zwraca obiekt formatowania dla tego obiektu TextFrame.<br/>            Tylko do odczytu [`ITextFrameFormat`](/slides/python-net/pl/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/itextframe/hyperlink_queries/) | Umożliwia łatwy dostęp do zawartych hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/pl/aspose.slides/itextframe/parent_shape/) | Zwraca rodzicielski kształt lub None, jeśli obiekt nadrzędny nie implementuje interfejsu IShape<br/>            Tylko do odczytu [`IShape`](/slides/python-net/pl/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/pl/aspose.slides/itextframe/parent_cell/) | Zwraca rodzicielski komórkę lub None, jeśli obiekt nadrzędny nie implementuje interfejsu ICell.<br/>            Tylko do odczytu [`ICell`](/slides/python-net/pl/aspose.slides/icell). |
| [`slide`](/slides/python-net/pl/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/itextframe/presentation/) |  |

## Metody

| Method | Opis |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/pl/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Wyróżnia wszystkie dopasowania przykładowego tekstu podanym kolorem. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/pl/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Wyróżnia wszystkie dopasowania przykładowego tekstu podanym kolorem. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/pl/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Wyróżnia wszystkie dopasowania przykładowego tekstu podanym kolorem. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/pl/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Wyróżnia wszystkie dopasowania wyrażenia regularnego podanym kolorem. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/pl/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Wyróżnia wszystkie dopasowania wyrażenia regularnego podanym kolorem. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Łączy fragmenty o tym samym formatowaniu we wszystkich paragrafach. |
| [`split_text_by_columns(self)`](/slides/python-net/pl/aspose.slides/itextframe/split_text_by_columns/#) | Rozdziela zawartość tekstową [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe) na tablicę łańcuchów,  <br/>            gdzie każdy element odpowiada osobnej kolumnie tekstowej w ramce. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/pl/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/pl/aspose.slides/itextframe/replace_regex/#str-str) | Zastępuje wszystkie dopasowania wyrażenia regularnego określonym łańcuchem. |


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)