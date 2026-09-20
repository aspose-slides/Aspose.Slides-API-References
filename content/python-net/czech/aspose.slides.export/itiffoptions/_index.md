---
title: ITiffOptions class
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides.export/itiffoptions/
---
## třída ITiffOptions

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu TIFF.

Typ ITiffOptions obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`image_size`](/slides/python-net/cs/aspose.slides.export/itiffoptions/image_size/) | Určuje velikost generovaného TIFF obrazu.<br/>            Výchozí hodnota je 0x0, což znamená, že velikosti generovaných obrázků budou vypočítány na základě velikosti snímku prezentace.<br/>            Čtení/zápis **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/cs/aspose.slides.export/itiffoptions/dpi_x/) | Určuje horizontální rozlišení v bodech na palec.<br/>            Čtení/zápis **int**. |
| [`dpi_y`](/slides/python-net/cs/aspose.slides.export/itiffoptions/dpi_y/) | Určuje vertikální rozlišení v bodech na palec.<br/>            Čtení/zápis **int**. |
| [`show_hidden_slides`](/slides/python-net/cs/aspose.slides.export/itiffoptions/show_hidden_slides/) | Určuje, zda má generovaný dokument zahrnovat skryté snímky nebo ne.<br/>            Výchozí hodnota je `false`. |
| [`compression_type`](/slides/python-net/cs/aspose.slides.export/itiffoptions/compression_type/) | Určuje typ komprese.<br/>            Čtení/zápis [`TiffCompressionTypes`](/slides/python-net/cs/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/cs/aspose.slides.export/itiffoptions/pixel_format/) | Určuje formát pixelů pro generované obrázky.<br/>            Čtení/zápis [`ImagePixelFormat`](/slides/python-net/cs/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/cs/aspose.slides.export/itiffoptions/slides_layout_options/) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [`ISlidesLayoutOptions`](/slides/python-net/cs/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/cs/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Určuje algoritmus pro převod barevného obrázku na černobílý obrázek.<br/>            Tato volba bude použita pouze pokud je [`ITiffOptions.compression_type`](/slides/python-net/cs/aspose.slides.export/itiffoptions/compression_type) <br/>            nastaveno na [`TiffCompressionTypes.CCITT4`](/slides/python-net/cs/aspose.slides.export/tiffcompressiontypes/CCITT4) nebo [`TiffCompressionTypes.CCITT3`](/slides/python-net/cs/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Čtení/zápis [`BlackWhiteConversionMode`](/slides/python-net/cs/aspose.slides.export/blackwhiteconversionmode).<br/>            Výchozí hodnota je [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/cs/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/cs/aspose.slides.export/itiffoptions/ink_options/) | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu.<br/>            Pouze pro čtení [`IInkOptions`](/slides/python-net/cs/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Viz také
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)