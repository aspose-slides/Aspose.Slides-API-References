---
title: IHtmlFormattingController class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController klasse

Beheert de generatie van een html-bestand.

Het type IHtmlFormattingController stelt de volgende leden beschikbaar:

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/nl/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Wordt aangeroepen om de html-documentkop te schrijven. Wordt één keer per presentatieconversie aangeroepen. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/nl/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Wordt aangeroepen om de html-documentvoettekst te schrijven. Wordt één keer per presentatieconversie aangeroepen. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/nl/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Wordt aangeroepen om de html-dia-kop te schrijven. Wordt één keer per dia aangeroepen. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/nl/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Wordt aangeroepen om de html-dia-voettekst te schrijven. Wordt één keer per dia aangeroepen. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/nl/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Wordt aangeroepen vóór het renderen van een shape. Wordt één keer per shape aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige dia-afbeeldingsgeneratie voltooid, wordt het toegevoegde html-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/nl/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Wordt aangeroepen vóór het renderen van een shape. Wordt één keer per shape aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige dia-afbeeldingsgeneratie voltooid, wordt het toegevoegde html-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart. |


### Zie ook
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)