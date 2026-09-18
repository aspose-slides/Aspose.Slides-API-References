---
title: TextFrame class
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/textframe/
---
## TextFrame osztály

Egy TextFrame-et képvisel.

A TextFrame típusa a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`paragraphs`](/slides/python-net/hu/aspose.slides/textframe/paragraphs/) | Visszaadja egy keret összes bekezdésének listáját.<br/>            Read-only [`IParagraphCollection`](/slides/python-net/hu/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/hu/aspose.slides/textframe/text/) | Lekéri vagy beállítja egy TextFrame egyszerű szövegét.<br/>            Read/write **str**. |
| [`text_frame_format`](/slides/python-net/hu/aspose.slides/textframe/text_frame_format/) | Visszaadja a formázási objektumot ehhez a TextFrame objektumhoz.<br/>            Read-only [`ITextFrameFormat`](/slides/python-net/hu/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/textframe/hyperlink_queries/) | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/hu/aspose.slides/textframe/slide/) | Visszaadja egy TextFrame szülő diáját.<br/>            Read-only [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/textframe/presentation/) | Visszaadja egy TextFrame szülő bemutatóját.<br/>            Read-only [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/hu/aspose.slides/textframe/parent_shape/) | Visszaadja a szülő alakzatot, vagy None-t, ha a szülő objektum nem valósítja meg az IShape interfészt<br/>            Read-only [`IShape`](/slides/python-net/hu/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/hu/aspose.slides/textframe/parent_cell/) | Visszaadja a szülő cellát, vagy None-t, ha a szülő objektum nem valósítja meg az ICell interfészt.<br/>            Read-only [`ICell`](/slides/python-net/hu/aspose.slides/icell). |

## Módszerek

| Metódus | Leírás |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hu/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/hu/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hu/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/hu/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hu/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/textframe/join_portions_with_same_formatting/#) | Összekapcsolja a hasonló formázású run-okat az összes bekezdésben. |
| [`split_text_by_columns(self)`](/slides/python-net/hu/aspose.slides/textframe/split_text_by_columns/#) | Felosztja a(z) [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe) szövegtartalmát egy karakterlánc tömbbe, <br/>            ahol minden elem a kereten belül egy külön szövegoszlopnak felel meg. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hu/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hu/aspose.slides/textframe/replace_regex/#str-str) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)