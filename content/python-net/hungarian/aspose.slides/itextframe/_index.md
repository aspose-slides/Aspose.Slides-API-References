---
title: ITextFrame class
second_title: Aspose.Slides a Python számára a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/itextframe/
---
## ITextFrame osztály

Egy TextFrame-et képvisel.

Az ITextFrame típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/hu/aspose.slides/itextframe/paragraphs/) | Visszaadja a keretben levő összes bekezdés listáját.<br/>            Csak olvasható [`IParagraphCollection`](/slides/python-net/hu/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/hu/aspose.slides/itextframe/text/) | Lekérdezi vagy beállítja a TextFrame egyszerű szövegét.<br/>            Olvasás/írás **str**. |
| [`text_frame_format`](/slides/python-net/hu/aspose.slides/itextframe/text_frame_format/) | Visszaadja a formázási objektumot ehhez a TextFrame objektumhoz.<br/>            Csak olvasható [`ITextFrameFormat`](/slides/python-net/hu/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/itextframe/hyperlink_queries/) | Egyszerű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/hu/aspose.slides/itextframe/parent_shape/) | Visszaadja a szülő alakzatot, vagy None értéket, ha a szülő objektum nem valósítja meg az IShape interfészt<br/>            Csak olvasható [`IShape`](/slides/python-net/hu/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/hu/aspose.slides/itextframe/parent_cell/) | Visszaadja a szülő cellát, vagy None értéket, ha a szülő objektum nem valósítja meg az ICell interfészt.<br/>            Csak olvasható [`ICell`](/slides/python-net/hu/aspose.slides/icell). |
| [`slide`](/slides/python-net/hu/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/itextframe/presentation/) |  |

## Metódusok

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hu/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Kiemeli a minta szöveg összes előfordulását a megadott színnel. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/hu/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Kiemeli a minta szöveg összes előfordulását a megadott színnel. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hu/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Kiemeli a minta szöveg összes előfordulását a megadott színnel. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hu/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/hu/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Összevonja a formázásban megegyező futamokat az összes bekezdésben. |
| [`split_text_by_columns(self)`](/slides/python-net/hu/aspose.slides/itextframe/split_text_by_columns/#) | Szétbontja a [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe) szövegtartalmát karakterlánc-tömbbé, <br/>            ahol minden elem a kereten belül egy külön szövegoszlopnak felel meg. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hu/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hu/aspose.slides/itextframe/replace_regex/#str-str) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)