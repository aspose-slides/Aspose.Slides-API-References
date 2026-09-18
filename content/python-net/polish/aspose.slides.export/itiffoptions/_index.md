---
title: ITiffOptions class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.export/itiffoptions/
---
## ITiffOptions klasa

Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie TIFF.

Typ ITiffOptions udostępnia następujące elementy:

## Właściwości

| Property | Opis |
| :- | :- |
| [`image_size`](/slides/python-net/pl/aspose.slides.export/itiffoptions/image_size/) | Określa rozmiar wygenerowanego obrazu TIFF.<br/>            Domyślna wartość to 0x0, co oznacza, że rozmiary wygenerowanego obrazu będą obliczane na podstawie wartości rozmiaru slajdu prezentacji.<br/>            Odczyt/zapis **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/pl/aspose.slides.export/itiffoptions/dpi_x/) | Określa rozdzielczość poziomą w punktach na cal.<br/>            Odczyt/zapis **int**. |
| [`dpi_y`](/slides/python-net/pl/aspose.slides.export/itiffoptions/dpi_y/) | Określa rozdzielczość pionową w punktach na cal.<br/>            Odczyt/zapis **int**. |
| [`show_hidden_slides`](/slides/python-net/pl/aspose.slides.export/itiffoptions/show_hidden_slides/) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy.<br/>            Domyślnie `false`. |
| [`compression_type`](/slides/python-net/pl/aspose.slides.export/itiffoptions/compression_type/) | Określa typ kompresji.<br/>            Odczyt/zapis [`TiffCompressionTypes`](/slides/python-net/pl/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/pl/aspose.slides.export/itiffoptions/pixel_format/) | Określa format pikseli dla wygenerowanych obrazów.<br/>            Odczyt/zapis [`ImagePixelFormat`](/slides/python-net/pl/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/pl/aspose.slides.export/itiffoptions/slides_layout_options/) | Pobiera lub ustawia tryb rozmieszczania slajdów na stronie podczas eksportu prezentacji [`ISlidesLayoutOptions`](/slides/python-net/pl/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/pl/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Określa algorytm konwersji obrazu kolorowego do obrazu czarno-białego.<br/>            Ta opcja zostanie zastosowana tylko jeśli [`ITiffOptions.compression_type`](/slides/python-net/pl/aspose.slides.export/itiffoptions/compression_type) <br/>            jest ustawione na [`TiffCompressionTypes.CCITT4`](/slides/python-net/pl/aspose.slides.export/tiffcompressiontypes/CCITT4) lub [`TiffCompressionTypes.CCITT3`](/slides/python-net/pl/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Odczyt/zapis [`BlackWhiteConversionMode`](/slides/python-net/pl/aspose.slides.export/blackwhiteconversionmode).<br/>            Domyślnie [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/pl/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/pl/aspose.slides.export/itiffoptions/ink_options/) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie.<br/>            Tylko do odczytu [`IInkOptions`](/slides/python-net/pl/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |


### Zobacz także
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)