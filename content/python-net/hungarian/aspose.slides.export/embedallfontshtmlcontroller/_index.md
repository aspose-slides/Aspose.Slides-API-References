---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides Pythonhoz a .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController osztály

Formázó vezérlő osztály a prezentáció összes betűtípusa WOFF formátumban való beágyazásához.

Az EmbedAllFontsHtmlController típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Új példányt hoz létre |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Új példányt hoz létre |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Az html dokumentum fejlécének írásához hívják. Egy prezentáció átalakításánként egyszer hívják. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Az html dokumentum láblécének írásához hívják. Egy prezentáció átalakításánként egyszer hívják. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Az html dia fejlécének írásához hívják. Minden dia esetén egyszer hívják. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Az html dia láblécének írásához hívják. Minden dia esetén egyszer hívják. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | A shape megjelenítése előtt hívják. Minden shape esetén egyszer hívják. Ha ez a függvény bármit ír a generatorba, az aktuális dia kép generálása befejeződik, a hozzáadott html töredék beillesztésre kerül, és egy új kép indul a korábbi tetején. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | A shape megjelenítése előtt hívják. Minden shape esetén egyszer hívják. Ha ez a függvény bármit ír a generatorba, az aktuális dia kép generálása befejeződik, a hozzáadott html töredék beillesztésre kerül, és egy új kép indul a korábbi tetején. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Az összes betűtípust írja a [`Presentation`](/slides/python-net/hu/aspose.slides/presentation)-ből. |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Az adatokat base64-ként a HTML dokumentumba írja. |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)