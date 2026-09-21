---
title: TiffOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/tiffoptions/
---
## TiffOptions klasse

Biedt opties die regelen hoe een presentatie wordt opgeslagen in TIFF-formaat.

**Erfelijkheid:**[`TiffOptions`](/slides/python-net/nl/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)

Het type TiffOptions bevat de volgende leden:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.export/tiffoptions/__init__/#) | Standaardconstructor. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`warning_callback`](/slides/python-net/nl/aspose.slides.export/tiffoptions/warning_callback/) | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken.<br/>            Lezen/Schrijven [`IWarningCallback`](/slides/python-net/nl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/nl/aspose.slides.export/tiffoptions/progress_callback/) | Vertegenwoordigt een callback-object voor het opslaan van voortgangsupdates in procenten.<br/>            Zie [`IProgressCallback`](/slides/python-net/nl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/nl/aspose.slides.export/tiffoptions/default_regular_font/) | Retourneert of stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden.<br/>            Lezen-schrijven **str**. |
| [`gradient_style`](/slides/python-net/nl/aspose.slides.export/tiffoptions/gradient_style/) | Retourneert of stelt de visuele stijl van de gradiënt in.<br/>            Lezen/Schrijven [`GradientStyle`](/slides/python-net/nl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/nl/aspose.slides.export/tiffoptions/skip_java_script_links/) | Geeft aan of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie.<br/>            Lezen/Schrijven **bool**. De standaardwaarde is **false** . |
| [`ink_options`](/slides/python-net/nl/aspose.slides.export/tiffoptions/ink_options/) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.<br/>            Alleen-lezen [`IInkOptions`](/slides/python-net/nl/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/nl/aspose.slides.export/tiffoptions/show_hidden_slides/) | Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet.<br/>            Standaard is `false`. |
| [`image_size`](/slides/python-net/nl/aspose.slides.export/tiffoptions/image_size/) | Specificeert de grootte van een gegenereerde TIFF-afbeelding.<br/>            Standaardwaarde is 0x0, wat betekent dat de gegenereerde afbeeldingsgroottes worden berekend op basis van de dia-grootte van de presentatie.<br/>            Lezen/Schrijven **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/nl/aspose.slides.export/tiffoptions/dpi_x/) | Specificeert de horizontale resolutie in dots per inch.<br/>            Lezen/Schrijven **int**. |
| [`dpi_y`](/slides/python-net/nl/aspose.slides.export/tiffoptions/dpi_y/) | Specificeert de verticale resolutie in dots per inch.<br/>            Lezen/Schrijven **int**. |
| [`compression_type`](/slides/python-net/nl/aspose.slides.export/tiffoptions/compression_type/) | Specificeert het compressietype.<br/>            Lezen/Schrijven [`TiffCompressionTypes`](/slides/python-net/nl/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/nl/aspose.slides.export/tiffoptions/pixel_format/) | Specificeert het pixelformaat voor de gegenereerde afbeeldingen.<br/>            Lezen/Schrijven [`ImagePixelFormat`](/slides/python-net/nl/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/nl/aspose.slides.export/tiffoptions/slides_layout_options/) | Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](/slides/python-net/nl/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/nl/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Specificeert het algoritme voor het converteren van een kleurenafbeelding naar een zwart-witbeeld.<br/>            Deze optie wordt alleen toegepast als [`TiffOptions.compression_type`](/slides/python-net/nl/aspose.slides.export/tiffoptions/compression_type) <br/>            is ingesteld op [`TiffCompressionTypes.CCITT4`](/slides/python-net/nl/aspose.slides.export/tiffcompressiontypes/CCITT4) of [`TiffCompressionTypes.CCITT3`](/slides/python-net/nl/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Lezen/Schrijven [`BlackWhiteConversionMode`](/slides/python-net/nl/aspose.slides.export/blackwhiteconversionmode).<br/>            Standaard is [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/nl/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Zie ook
* klasse [`SaveOptions`](/slides/python-net/nl/aspose.slides.export/saveoptions)
* klasse [`TiffOptions`](/slides/python-net/nl/aspose.slides.export/tiffoptions)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)