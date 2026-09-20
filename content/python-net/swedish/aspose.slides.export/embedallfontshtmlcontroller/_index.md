---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController klass

Formateringskontrollerklass att använda för att bädda in alla presentationsfonter i WOFF-format.

Typen EmbedAllFontsHtmlController visar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Skapar ny instans |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Skapar ny instans |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Kallas för att skriva html-dokumentets rubrik. Kallas en gång per presentationskonvertering. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Kallas för att skriva html-dokumentets sidfot. Kallas en gång per presentationskonvertering. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Kallas för att skriva html-bildrubrik. Kallas en gång per varje bild. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Kallas för att skriva html-bildsidfot. Kallas en gång per varje bild. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Kallas innan figurens rendering. Kallas en gång per varje figur. Om denna funktion skriver något till generatorn avslutas den aktuella bildens bildgenerering, den tillagda html-fragmentet infogas och en ny bild påbörjas ovanpå den föregående. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Kallas innan figurens rendering. Kallas en gång per varje figur. Om denna funktion skriver något till generatorn avslutas den aktuella bildens bildgenerering, den tillagda html-fragmentet infogas och en ny bild påbörjas ovanpå den föregående. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Skriv alla fonter som finns i [`Presentation`](/slides/python-net/sv/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/sv/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Skriver data som base64 i HTML-dokumentet självt |


### Se även
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)