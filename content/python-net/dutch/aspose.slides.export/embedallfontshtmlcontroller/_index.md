---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController klasse

De opmaakcontrollerklasse die gebruikt wordt om alle presentatie-lettertypen in WOFF-formaat in te sluiten.

Het type EmbedAllFontsHtmlController biedt de volgende leden weer:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Maakt een nieuw exemplaar |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/nl/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Maakt een nieuw exemplaar |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/nl/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Wordt aangeroepen om de HTML-documentkop te schrijven. Wordt één keer per presentatieconversie aangeroepen. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/nl/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Wordt aangeroepen om de HTML-documentvoettekst te schrijven. Wordt één keer per presentatieconversie aangeroepen. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/nl/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Wordt aangeroepen om de HTML-slide-kop te schrijven. Wordt één keer per slide aangeroepen. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/nl/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Wordt aangeroepen om de HTML-slide-voettekst te schrijven. Wordt één keer per slide aangeroepen. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/nl/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Wordt aangeroepen vóór het renderen van een vorm. Wordt één keer per vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldingsgeneratie afgerond, wordt het toegevoegde HTML-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/nl/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Wordt aangeroepen vóór het renderen van een vorm. Wordt één keer per vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldingsgeneratie afgerond, wordt het toegevoegde HTML-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/nl/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Schrijf alle lettertypen die voorkomen in [`Presentation`](/slides/python-net/nl/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/nl/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Schrijft data als base64 in het HTML-document zelf |

### Zie ook
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)