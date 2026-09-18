---
title: TiffOptions class
second_title: Aspose.Slides dla Pythona za pośrednictwem referencji API .NET
description: 
type: docs
url: /pl/aspose.slides.export/tiffoptions/
---
## TiffOptions klasa

Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie TIFF.

**Dziedziczenie:**[`TiffOptions`](/slides/python-net/pl/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)

Typ TiffOptions udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/tiffoptions/__init__/#) | Domyślny konstruktor. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/tiffoptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany.<br/>            Odczyt/zapis [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/tiffoptions/progress_callback/) | Reprezentuje obiekt wywołania zwrotnego dla aktualizacji postępu zapisu w procentach.<br/>            Zobacz [`IProgressCallback`](/slides/python-net/pl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/tiffoptions/default_regular_font/) | Zwraca lub ustawia czcionkę używaną w przypadku, gdy nie odnaleziono czcionki źródłowej.<br/>            Odczyt/zapis **str**. |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/tiffoptions/gradient_style/) | Zwraca lub ustawia styl wizualny gradientu.<br/>            Odczyt/zapis [`GradientStyle`](/slides/python-net/pl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/tiffoptions/skip_java_script_links/) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji.<br/>            Odczyt/zapis **bool**. Domyślna wartość to **false**. |
| [`ink_options`](/slides/python-net/pl/aspose.slides.export/tiffoptions/ink_options/) | Zapewnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie.<br/>            Tylko do odczytu [`IInkOptions`](/slides/python-net/pl/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/pl/aspose.slides.export/tiffoptions/show_hidden_slides/) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie.<br/>            Domyślna wartość to `false`. |
| [`image_size`](/slides/python-net/pl/aspose.slides.export/tiffoptions/image_size/) | Określa rozmiar wygenerowanego obrazu TIFF.<br/>            Domyślna wartość to 0x0, co oznacza, że rozmiary wygenerowanego obrazu będą obliczane na podstawie rozmiaru slajdu prezentacji.<br/>            Odczyt/zapis **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/pl/aspose.slides.export/tiffoptions/dpi_x/) | Określa poziomą rozdzielczość w punktach na cal.<br/>            Odczyt/zapis **int**. |
| [`dpi_y`](/slides/python-net/pl/aspose.slides.export/tiffoptions/dpi_y/) | Określa pionową rozdzielczość w punktach na cal.<br/>            Odczyt/zapis **int**. |
| [`compression_type`](/slides/python-net/pl/aspose.slides.export/tiffoptions/compression_type/) | Określa typ kompresji.<br/>            Odczyt/zapis [`TiffCompressionTypes`](/slides/python-net/pl/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/pl/aspose.slides.export/tiffoptions/pixel_format/) | Określa format pikseli dla wygenerowanych obrazów.<br/>            Odczyt/zapis [`ImagePixelFormat`](/slides/python-net/pl/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/pl/aspose.slides.export/tiffoptions/slides_layout_options/) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie przy eksporcie prezentacji [`ISlidesLayoutOptions`](/slides/python-net/pl/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/pl/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Określa algorytm konwertowania obrazu kolorowego na czarno-biały.<br/>            Ta opcja będzie zastosowana tylko jeśli [`TiffOptions.compression_type`](/slides/python-net/pl/aspose.slides.export/tiffoptions/compression_type) <br/>            ma wartość [`TiffCompressionTypes.CCITT4`](/slides/python-net/pl/aspose.slides.export/tiffcompressiontypes/CCITT4) lub [`TiffCompressionTypes.CCITT3`](/slides/python-net/pl/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Odczyt/zapis [`BlackWhiteConversionMode`](/slides/python-net/pl/aspose.slides.export/blackwhiteconversionmode).<br/>            Domyślna wartość to [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/pl/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Zobacz także
* klasa [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)
* klasa [`TiffOptions`](/slides/python-net/pl/aspose.slides.export/tiffoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)