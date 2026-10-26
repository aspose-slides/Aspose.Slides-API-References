---
title: TextFrame class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/textframe/
---
## TextFrame klasa

Reprezentuje TextFrame.

Typ TextFrame udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`paragraphs`](/slides/python-net/pl/aspose.slides/textframe/paragraphs/) | Zwraca listę wszystkich akapitów w ramce.<br/>            Tylko do odczytu [`IParagraphCollection`](/slides/python-net/pl/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/pl/aspose.slides/textframe/text/) | Pobiera lub ustawia zwykły tekst dla TextFrame.<br/>            Odczyt/zapis **str**. |
| [`text_frame_format`](/slides/python-net/pl/aspose.slides/textframe/text_frame_format/) | Zwraca obiekt formatowania tego obiektu TextFrame.<br/>            Tylko do odczytu [`ITextFrameFormat`](/slides/python-net/pl/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/textframe/hyperlink_queries/) | Zapewnia łatwy dostęp do zawartych hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/pl/aspose.slides/textframe/slide/) | Zwraca slajd nadrzędny TextFrame.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/textframe/presentation/) | Zwraca prezentację nadrzędną TextFrame.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/pl/aspose.slides/textframe/parent_shape/) | Zwraca kształt nadrzędny lub None, jeśli obiekt nadrzędny nie implementuje interfejsu IShape<br/>            Tylko do odczytu [`IShape`](/slides/python-net/pl/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/pl/aspose.slides/textframe/parent_cell/) | Zwraca komórkę nadrzędną lub None, jeśli obiekt nadrzędny nie implementuje interfejsu ICell.<br/>            Tylko do odczytu [`ICell`](/slides/python-net/pl/aspose.slides/icell). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/pl/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Podświetla wszystkie wystąpienia przykładowego tekstu określonym kolorem. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/pl/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Podświetla wszystkie wystąpienia przykładowego tekstu określonym kolorem. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/pl/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Podświetla wszystkie wystąpienia przykładowego tekstu określonym kolorem. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/pl/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/pl/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/textframe/join_portions_with_same_formatting/#) | Łączy segmenty o tym samym formatowaniu we wszystkich akapitach. |
| [`split_text_by_columns(self)`](/slides/python-net/pl/aspose.slides/textframe/split_text_by_columns/#) | Dzieli zawartość tekstową [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe) na tablicę łańcuchów znaków,  <br/>            gdzie każdy element odpowiada osobnej kolumnie tekstowej w ramce. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/pl/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/pl/aspose.slides/textframe/replace_regex/#str-str) | Zastępuje wszystkie dopasowania wyrażenia regularnego określonym ciągiem. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)