---
title: IHtmlFormattingController class
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController osztály

HTML fájl generálását vezérli.

Az IHtmlFormattingController típus a következő tagokat teszi közzé:

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/hu/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | HTML dokumentum fejlécének írására hívják. Minden prezentáció átalakításakor egyszer hívják. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/hu/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | HTML dokumentum láblécének írására hívják. Minden prezentáció átalakításakor egyszer hívják. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/hu/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | HTML dia fejlécének írására hívják. Minden dián egyszer hívják. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/hu/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | HTML dia láblécének írására hívják. Minden dián egyszer hívják. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/hu/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | A forma renderelése előtt hívják. Minden formán egyszer hívják. Ha ez a függvény bármit ír a generátorba, a jelenlegi dia képgenerálása befejeződik, a hozzáadott html fragmentum beillesztődik, és egy új kép indul a korábbi tetején. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/hu/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | A forma renderelése előtt hívják. Minden formán egyszer hívják. Ha ez a függvény bármit ír a generátorba, a jelenlegi dia képgenerálása befejeződik, a hozzáadott html fragmentum beillesztődik, és egy új kép indul a korábbi tetején. |


### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)