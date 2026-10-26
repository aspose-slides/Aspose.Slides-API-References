---
title: TextFrame class
second_title: Aspose.Slides a Python számára .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides/textframe/
---
## TextFrame osztály

A TextFrame-et képviseli.

A TextFrame típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`paragraphs`](/slides/python-net/hu/aspose.slides/textframe/paragraphs/) | Visszaadja a keretben lévő összes bekezdés listáját.<br/>            Csak olvasható [`IParagraphCollection`](/slides/python-net/hu/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/hu/aspose.slides/textframe/text/) | Lekéri vagy beállítja a TextFrame egyszerű szövegét.<br/>            Olvasás/írás **str**. |
| [`text_frame_format`](/slides/python-net/hu/aspose.slides/textframe/text_frame_format/) | Visszaadja a formázási objektumot ehhez a TextFrame objektumhoz.<br/>            Csak olvasható [`ITextFrameFormat`](/slides/python-net/hu/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/textframe/hyperlink_queries/) | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/hu/aspose.slides/textframe/slide/) | Visszaadja a TextFrame szülő diaját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/textframe/presentation/) | Visszaadja a TextFrame szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/hu/aspose.slides/textframe/parent_shape/) | Visszaadja a szülő alakzatot, vagy None értéket, ha a szülő objektum nem valósítja meg az IShape interfészt<br/>            Csak olvasható [`IShape`](/slides/python-net/hu/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/hu/aspose.slides/textframe/parent_cell/) | Visszaadja a szülő cellát, vagy None értéket, ha a szülő objektum nem valósítja meg az ICell interfészt.<br/>            Csak olvasható [`ICell`](/slides/python-net/hu/aspose.slides/icell). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hu/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/hu/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hu/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/hu/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hu/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/textframe/join_portions_with_same_formatting/#) | Összefűzi az azonos formázású futásokat az összes bekezdésben. |
| [`split_text_by_columns(self)`](/slides/python-net/hu/aspose.slides/textframe/split_text_by_columns/#) | Felosztja a [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe) szövegtartalmát karakterláncok tömbjébe, <br/>            ahol minden elem a kereten belüli különálló szövegoszlopnak felel meg. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hu/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hu/aspose.slides/textframe/replace_regex/#str-str) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)