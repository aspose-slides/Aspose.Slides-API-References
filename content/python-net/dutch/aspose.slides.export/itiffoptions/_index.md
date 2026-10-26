---
title: ITiffOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/itiffoptions/
---
## ITiffOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in TIFF-indeling.

Het ITiffOptions-type exposeert de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`image_size`](/slides/python-net/nl/aspose.slides.export/itiffoptions/image_size/) | Specificeert de grootte van een gegenereerde TIFF-afbeelding.<br/>            Standaardwaarde is 0x0, wat betekent dat de grootte van de gegenereerde afbeelding wordt berekend op basis van de grootte van de presentatieslide.<br/>            Lezen/schrijven [`Size`](/slides/python-net/nl/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/nl/aspose.slides.export/itiffoptions/dpi_x/) | Specificeert de horizontale resolutie in punten per inch.<br/>            Lezen/schrijven **int**. |
| [`dpi_y`](/slides/python-net/nl/aspose.slides.export/itiffoptions/dpi_y/) | Specificeert de verticale resolutie in punten per inch.<br/>            Lezen/schrijven **int**. |
| [`show_hidden_slides`](/slides/python-net/nl/aspose.slides.export/itiffoptions/show_hidden_slides/) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet.<br/>            Standaard is `false`. |
| [`compression_type`](/slides/python-net/nl/aspose.slides.export/itiffoptions/compression_type/) | Specificeert het compressietype.<br/>            Lezen/schrijven [`TiffCompressionTypes`](/slides/python-net/nl/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/nl/aspose.slides.export/itiffoptions/pixel_format/) | Specificeert het pixelformaat voor de gegenereerde afbeeldingen.<br/>            Lezen/schrijven [`ImagePixelFormat`](/slides/python-net/nl/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/nl/aspose.slides.export/itiffoptions/slides_layout_options/) | Haalt of stelt de modus op waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](/slides/python-net/nl/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/nl/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Specificeert het algoritme voor het omzetten van een kleurenafbeelding naar een zwart-wit afbeelding.<br/>            Deze optie wordt alleen toegepast als [`ITiffOptions.compression_type`](/slides/python-net/nl/aspose.slides.export/itiffoptions/compression_type) <br/>            is ingesteld op [`TiffCompressionTypes.CCITT4`](/slides/python-net/nl/aspose.slides.export/tiffcompressiontypes/CCITT4) of [`TiffCompressionTypes.CCITT3`](/slides/python-net/nl/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Lezen/schrijven [`BlackWhiteConversionMode`](/slides/python-net/nl/aspose.slides.export/blackwhiteconversionmode).<br/>            Standaard is [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/nl/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/nl/aspose.slides.export/itiffoptions/ink_options/) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.<br/>            Alleen-lezen [`IInkOptions`](/slides/python-net/nl/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/nl/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/nl/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/nl/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/nl/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Zie ook
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)