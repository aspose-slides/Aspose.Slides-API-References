---
title: IHtmlFormattingController class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController třída

Řídí generování html souboru.

Typ IHtmlFormattingController vystavuje následující členy:

## Metody

| Metoda | Popis |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/cs/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Volá se k zápisu hlavičky html dokumentu. Volá se jednou na každou konverzi prezentace. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/cs/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Volá se k zápisu patičky html dokumentu. Volá se jednou na každou konverzi prezentace. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/cs/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Volá se k zápisu hlavičky html snímku. Volá se jednou u každého snímku. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/cs/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Volá se k zápisu patičky html snímku. Volá se jednou u každého snímku. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/cs/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Volá se před vykreslením tvaru. Volá se jednou u každého tvaru. Pokud tato funkce zapíše něco do generátoru, generování obrázku aktuálního snímku bude dokončeno, vloží se přidaný html fragment a nový obrázek bude zahájen nad předchozím. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/cs/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Volá se před vykreslením tvaru. Volá se jednou u každého tvaru. Pokud tato funkce zapíše něco do generátoru, generování obrázku aktuálního snímku bude dokončeno, vloží se přidaný html fragment a nový obrázek bude zahájen nad předchozím. |

### Viz také
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)