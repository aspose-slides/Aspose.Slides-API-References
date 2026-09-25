---
title: TiffOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/tiffoptions/
---
## TiffOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.

**Arv:**[`TiffOptions`](/slides/python-net/sv/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)

TiffOptions-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.export/tiffoptions/__init__/#) | Standardkonstruktor. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/tiffoptions/warning_callback/) | Returnerar eller sätter ett objekt som tar emot varningar och bestämmer om inläsningsprocessen ska fortsätta eller avbrytas.<br/>            Läs/skriv [`IWarningCallback`](/slides/python-net/sv/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/tiffoptions/progress_callback/) | Representerar ett återuppringningsobjekt för att spara förloppsuppdateringar i procent.<br/>            Se [`IProgressCallback`](/slides/python-net/sv/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/tiffoptions/default_regular_font/) | Returnerar eller sätter typsnitt som används om källtypsnittet inte hittas.<br/>            Läs/skriv **str**. |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/tiffoptions/gradient_style/) | Returnerar eller sätter den visuella stilen för gradienten.<br/>            Läs/skriv [`GradientStyle`](/slides/python-net/sv/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/tiffoptions/skip_java_script_links/) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. <br/>            Läs/skriv **bool**. Standardvärdet är **false**. |
| [`ink_options`](/slides/python-net/sv/aspose.slides.export/tiffoptions/ink_options/) | Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument.<br/>            Skrivskyddad [`IInkOptions`](/slides/python-net/sv/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/sv/aspose.slides.export/tiffoptions/show_hidden_slides/) | Anger om det genererade dokumentet ska inkludera dolda bildspel eller inte.<br/>            Standard är `false`. |
| [`image_size`](/slides/python-net/sv/aspose.slides.export/tiffoptions/image_size/) | Anger storleken på en genererad TIFF-bild.<br/>            Standardvärdet är 0x0, vilket betyder att genererade bildstorlekar beräknas baserat på presentationsbildens storlek.<br/>            Läs/skriv [`Size`](/slides/python-net/sv/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/sv/aspose.slides.export/tiffoptions/dpi_x/) | Anger den horisontella upplösningen i punkter per tum.<br/>            Läs/skriv **int**. |
| [`dpi_y`](/slides/python-net/sv/aspose.slides.export/tiffoptions/dpi_y/) | Anger den vertikala upplösningen i punkter per tum.<br/>            Läs/skriv **int**. |
| [`compression_type`](/slides/python-net/sv/aspose.slides.export/tiffoptions/compression_type/) | Anger komprimeringstypen.<br/>            Läs/skriv [`TiffCompressionTypes`](/slides/python-net/sv/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/sv/aspose.slides.export/tiffoptions/pixel_format/) | Anger pixelformatet för de genererade bilderna.<br/>            Läs/skriv [`ImagePixelFormat`](/slides/python-net/sv/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/sv/aspose.slides.export/tiffoptions/slides_layout_options/) | Hämtar eller sätter läget i vilket bildspel placeras på sidan vid export av en presentation [`ISlidesLayoutOptions`](/slides/python-net/sv/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/sv/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Anger algoritmen för att konvertera en färgbild till en svart-vit bild.<br/>            Detta alternativ tillämpas endast om [`TiffOptions.compression_type`](/slides/python-net/sv/aspose.slides.export/tiffoptions/compression_type) <br/>            är satt till [`TiffCompressionTypes.CCITT4`](/slides/python-net/sv/aspose.slides.export/tiffcompressiontypes/CCITT4) eller [`TiffCompressionTypes.CCITT3`](/slides/python-net/sv/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Läs/skriv [`BlackWhiteConversionMode`](/slides/python-net/sv/aspose.slides.export/blackwhiteconversionmode).<br/>            Standard är [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/sv/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Se även
* klass [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)
* klass [`TiffOptions`](/slides/python-net/sv/aspose.slides.export/tiffoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)