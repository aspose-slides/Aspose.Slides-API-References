---
title: IHtmlFormattingController class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController klass

Styr generering av en html-fil.

Typen IHtmlFormattingController exponerar följande medlemmar:

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/sv/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Kallas för att skriva html-dokumenthuvud. Kallas en gång per presentationens konvertering. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/sv/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Kallas för att skriva html-dokumentfot. Kallas en gång per presentationens konvertering. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/sv/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Kallas för att skriva html-bildhuvud. Kallas en gång per varje bild. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/sv/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Kallas för att skriva html-bildfot. Kallas en gång per varje bild. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/sv/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Kallas innan formens rendering. Kallas en gång per varje form. Om denna funktion skriver något till generatorn, avslutas den aktuella bildens bildgenerering, det tillagda html-fragmentet infogas och en ny bild startas ovanpå den föregående. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/sv/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Kallas innan formens rendering. Kallas en gång per varje form. Om denna funktion skriver något till generatorn, avslutas den aktuella bildens bildgenerering, det tillagda html-fragmentet infogas och en ny bild startas ovanpå den föregående. |


### Se även
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)