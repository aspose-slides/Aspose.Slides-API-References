---
title: TiffOptions class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/tiffoptions/
---
## TiffOptions třída

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu TIFF.

**Dědičnost:**[`TiffOptions`](/slides/python-net/cs/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)

Typ TiffOptions vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/tiffoptions/__init__/#) | Výchozí konstruktor. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/tiffoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen.<br/>            Čtení/zápis [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/tiffoptions/progress_callback/) | Representuje objekt zpětného volání pro ukládání aktualizací postupu v procentech.<br/>            Viz [`IProgressCallback`](/slides/python-net/cs/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/tiffoptions/default_regular_font/) | Vrací nebo nastavuje písmo použité, pokud není nalezeno zdrojové písmo.<br/>            Čtení/zápis **str**. |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/tiffoptions/gradient_style/) | Vrací nebo nastavuje vizuální styl gradientu.<br/>            Čtení/zápis [`GradientStyle`](/slides/python-net/cs/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/tiffoptions/skip_java_script_links/) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu.<br/>            Čtení/zápis **bool**. Výchozí hodnota je **false**. |
| [`ink_options`](/slides/python-net/cs/aspose.slides.export/tiffoptions/ink_options/) | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu.<br/>            Pouze pro čtení [`IInkOptions`](/slides/python-net/cs/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/cs/aspose.slides.export/tiffoptions/show_hidden_slides/) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, či nikoliv.<br/>            Výchozí hodnota je `false`. |
| [`image_size`](/slides/python-net/cs/aspose.slides.export/tiffoptions/image_size/) | Určuje velikost vygenerovaného TIFF obrázku.<br/>            Výchozí hodnota je 0x0, což znamená, že velikosti vygenerovaných obrázků budou vypočítány na základě velikosti snímku prezentace.<br/>            Čtení/zápis [`Size`](/slides/python-net/cs/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/cs/aspose.slides.export/tiffoptions/dpi_x/) | Určuje horizontální rozlišení v bodech na palec.<br/>            Čtení/zápis **int**. |
| [`dpi_y`](/slides/python-net/cs/aspose.slides.export/tiffoptions/dpi_y/) | Určuje vertikální rozlišení v bodech na palec.<br/>            Čtení/zápis **int**. |
| [`compression_type`](/slides/python-net/cs/aspose.slides.export/tiffoptions/compression_type/) | Určuje typ komprese.<br/>            Čtení/zápis [`TiffCompressionTypes`](/slides/python-net/cs/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/cs/aspose.slides.export/tiffoptions/pixel_format/) | Určuje formát pixelů pro vygenerované obrázky.<br/>            Čtení/zápis [`ImagePixelFormat`](/slides/python-net/cs/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/cs/aspose.slides.export/tiffoptions/slides_layout_options/) | Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [`ISlidesLayoutOptions`](/slides/python-net/cs/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/cs/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Určuje algoritmus pro převod barevného obrázku na černobílý obrázek.<br/>            Tato možnost bude použita jen pokud [`TiffOptions.compression_type`](/slides/python-net/cs/aspose.slides.export/tiffoptions/compression_type) <br/>            je nastaven na [`TiffCompressionTypes.CCITT4`](/slides/python-net/cs/aspose.slides.export/tiffcompressiontypes/CCITT4) nebo [`TiffCompressionTypes.CCITT3`](/slides/python-net/cs/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Čtení/zápis [`BlackWhiteConversionMode`](/slides/python-net/cs/aspose.slides.export/blackwhiteconversionmode).<br/>            Výchozí hodnota je [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/cs/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Viz také
* třída [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)
* třída [`TiffOptions`](/slides/python-net/cs/aspose.slides.export/tiffoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)