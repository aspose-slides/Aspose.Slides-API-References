---
title: PptxOptions class
second_title: Aspose.Slides dla Pythona poprzez interfejs API .NET
description: 
type: docs
url: /pl/aspose.slides.export/pptxoptions/
---
## PptxOptions klasa

Reprezentuje opcje zapisywania prezentacji OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

**Dziedziczenie:**[`PptxOptions`](/slides/python-net/pl/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)

Typ PptxOptions udostępnia następujące członki:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/pptxoptions/__init__/#) | Creates new instance of PptxOptions |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/pptxoptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany.<br/>            Read/write [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/pptxoptions/progress_callback/) | Reprezentuje obiekt wywołania zwrotnego dla aktualizacji postępu zapisu w procentach.<br/>            See [`IProgressCallback`](/slides/python-net/pl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/pptxoptions/default_regular_font/) | Zwraca lub ustawia czcionkę używaną, gdy nie znaleziono czcionki źródłowej.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/pptxoptions/gradient_style/) | Zwraca lub ustawia styl wizualny gradientu.<br/>            Read/write [`GradientStyle`](/slides/python-net/pl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/pptxoptions/skip_java_script_links/) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji.<br/>            Read/write **bool**. Domyślna wartość to **false** . |
| [`conformance`](/slides/python-net/pl/aspose.slides.export/pptxoptions/conformance/) | Określa klasę zgodności, do której dokument Presentation jest zgodny.<br/>            Domyślna wartość to [`Conformance.ECMA_376_2006`](/slides/python-net/pl/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/pl/aspose.slides.export/pptxoptions/zip_64_mode/) | Określa, czy format ZIP64 jest używany dla dokumentu Presentation.<br/>            Domyślna wartość to [`Zip64Mode.IF_NECESSARY`](/slides/python-net/pl/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/pl/aspose.slides.export/pptxoptions/refresh_thumbnail/) | Określa, czy miniatura prezentacji będzie odświeżana.<br/>            Read/write **bool**.<br/>            Domyślna wartość to **true** . |
| [`compression_level`](/slides/python-net/pl/aspose.slides.export/pptxoptions/compression_level/) | Określa poziom kompresji używany przy zapisywaniu dokumentu prezentacji.<br/>            Domyślna wartość to [`CompressionLevel.LEVEL6`](/slides/python-net/pl/aspose.slides.export/compressionlevel/LEVEL6). |


### Zobacz także
* klasa [`PptxOptions`](/slides/python-net/pl/aspose.slides.export/pptxoptions)
* klasa [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)