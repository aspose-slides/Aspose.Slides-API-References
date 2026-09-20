---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController třída

Formátovací řadičová třída, která se používá pro vložení všech písem prezentace ve formátu WOFF.

Typ EmbedAllFontsHtmlController poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Vytvoří novou instanci |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/cs/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Vytvoří novou instanci |

## Metody

| Metoda | Popis |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/cs/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Voláno k zápisu hlavičky html dokumentu. Voláno jednou při každém převodu prezentace. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/cs/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Voláno k zápisu patičky html dokumentu. Voláno jednou při každém převodu prezentace. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/cs/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Voláno k zápisu hlavičky html snímku. Voláno jednou pro každý snímek. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/cs/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Voláno k zápisu patičky html snímku. Voláno jednou pro každý snímek. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/cs/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce zapíše něco do generátoru, generování obrázku aktuálního snímku bude dokončeno, přidaný html fragment bude vložen a nový obrázek bude zahájen nad předchozím. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/cs/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce zapíše něco do generátoru, generování obrázku aktuálního snímku bude dokončeno, přidaný html fragment bude vložen a nový obrázek bude zahájen nad předchozím. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/cs/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Zapíše všechna písma obsažená v [`Presentation`](/slides/python-net/cs/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/cs/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Zapíše data jako base64 přímo do HTML dokumentu. |


### Viz také
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)