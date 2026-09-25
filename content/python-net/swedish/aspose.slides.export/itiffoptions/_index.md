---
title: ITiffOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/itiffoptions/
---
## ITiffOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.

ITiffOptions-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`image_size`](/slides/python-net/sv/aspose.slides.export/itiffoptions/image_size/) | Anger storleken på en genererad TIFF-bild.<br/>            Standardvärdet är 0x0, vilket betyder att genererade bildstorlekar beräknas baserat på presentationsbildens storlek.<br/>            Läs/skriv [`Size`](/slides/python-net/sv/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/sv/aspose.slides.export/itiffoptions/dpi_x/) | Anger den horisontella upplösningen i punkter per tum.<br/>            Läs/skriv **int**. |
| [`dpi_y`](/slides/python-net/sv/aspose.slides.export/itiffoptions/dpi_y/) | Anger den vertikala upplösningen i punkter per tum.<br/>            Läs/skriv **int**. |
| [`show_hidden_slides`](/slides/python-net/sv/aspose.slides.export/itiffoptions/show_hidden_slides/) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte.<br/>            Standardvärdet är `false`. |
| [`compression_type`](/slides/python-net/sv/aspose.slides.export/itiffoptions/compression_type/) | Anger komprimeringstypen.<br/>            Läs/skriv [`TiffCompressionTypes`](/slides/python-net/sv/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/sv/aspose.slides.export/itiffoptions/pixel_format/) | Anger pixelformatet för de genererade bilderna.<br/>            Läs/skriv [`ImagePixelFormat`](/slides/python-net/sv/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/sv/aspose.slides.export/itiffoptions/slides_layout_options/) | Hämtar eller anger läget som bilder placeras på sidan i när en presentation exporteras [`ISlidesLayoutOptions`](/slides/python-net/sv/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/sv/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Anger algoritmen för att omvandla en färgbild till en svartvit bild.<br/>            Detta alternativ tillämpas endast om [`ITiffOptions.compression_type`](/slides/python-net/sv/aspose.slides.export/itiffoptions/compression_type) <br/>            är satt till [`TiffCompressionTypes.CCITT4`](/slides/python-net/sv/aspose.slides.export/tiffcompressiontypes/CCITT4) eller [`TiffCompressionTypes.CCITT3`](/slides/python-net/sv/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Läs/skriv [`BlackWhiteConversionMode`](/slides/python-net/sv/aspose.slides.export/blackwhiteconversionmode).<br/>            Standardvärdet är [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/sv/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/sv/aspose.slides.export/itiffoptions/ink_options/) | Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterat dokument.<br/>            Skrivskyddad [`IInkOptions`](/slides/python-net/sv/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Se även
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)