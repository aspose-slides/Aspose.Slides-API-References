---
title: Compress class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.lowcode/compress/
---
## Compress klasse

Stelt een groep methoden voor die bedoeld is om [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) te comprimeren.

Het Compress-type biedt de volgende leden:

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/nl/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Vermindert de grootte van een presentatie door alle beschikbare compressiestappen toe te passen:<br/>            <br/>* Verwijdert ongebruikte masterslides **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Verwijdert ongebruikte layoutslides **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Houdt alleen de glyphs die daadwerkelijk worden gebruikt in ingesloten lettertypen **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Vermindert de afbeeldingresolutie tot 150 DPI en verwijdert bijgesneden gebieden van afbeeldingen **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/nl/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Voert compressie uit op de [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) door ongebruikte masterslides te verwijderen. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/nl/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Voert compressie uit op de [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) door ongebruikte layoutslides te verwijderen. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/nl/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Voert compressie uit op de [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) door ongebruikte tekens uit ingesloten lettertypen te verwijderen. |
| [`compress_images(presentation, resolution)`](/slides/python-net/nl/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Vermindert de resolutie van afbeeldingen in de presentatie en verwijdert hun bijgesneden gebieden,<br/>            vergelijkbaar met PowerPoint's "Compress Pictures" toegepast op alle afbeeldingen.<br/>            Afbeeldingen op dia's, layoutslides en masterslides worden verwerkt, inclusief afbeeldingen binnen groepsvormen<br/>            en afbeeldingvullingen van vormen. |

### Zie ook
* klasse [`Presentation`](/slides/python-net/nl/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/nl/aspose.slides.lowcode)
* bibliotheek [`Aspose.Slides`](/slides/python-net)