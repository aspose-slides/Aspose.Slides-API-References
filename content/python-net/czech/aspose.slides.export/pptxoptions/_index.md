---
title: PptxOptions class
second_title: Aspose.Slides pro Python přes .NET – referenční dokumentace API
description: 
type: docs
url: /cs/aspose.slides.export/pptxoptions/
---
## PptxOptions třída

Reprezentuje možnosti pro ukládání prezentací OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

**Dědičnost:**[`PptxOptions`](/slides/python-net/cs/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)

Typ PptxOptions poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/pptxoptions/__init__/#) | Vytvoří novou instanci PptxOptions |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/pptxoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen.<br/>            Read/write [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/pptxoptions/progress_callback/) | Representuje objekt zpětného volání pro aktualizace průběhu ukládání v procentech.<br/>            Viz [`IProgressCallback`](/slides/python-net/cs/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/pptxoptions/default_regular_font/) | Vrací nebo nastavuje písmo použité v případě, že výchozí písmo nebylo nalezeno.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/pptxoptions/gradient_style/) | Vrací nebo nastavuje vizuální styl gradientu.<br/>            Read/write [`GradientStyle`](/slides/python-net/cs/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/pptxoptions/skip_java_script_links/) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu.<br/>            Read/write **bool**. Výchozí hodnota je **false**. |
| [`conformance`](/slides/python-net/cs/aspose.slides.export/pptxoptions/conformance/) | Určuje třídu shody, ke které dokument Presentation odpovídá.<br/>            Výchozí hodnota je [`Conformance.ECMA_376_2006`](/slides/python-net/cs/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/cs/aspose.slides.export/pptxoptions/zip_64_mode/) | Určuje, zda je pro dokument Presentation používán formát ZIP64.<br/>            Výchozí hodnota je [`Zip64Mode.IF_NECESSARY`](/slides/python-net/cs/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/cs/aspose.slides.export/pptxoptions/refresh_thumbnail/) | Určuje, zda bude miniatura prezentace obnovena.<br/>            Read/write **bool**.<br/>            Výchozí hodnota je **true** . |
| [`compression_level`](/slides/python-net/cs/aspose.slides.export/pptxoptions/compression_level/) | Určuje úroveň komprese použité při ukládání dokumentu prezentace.<br/>            Výchozí hodnota je [`CompressionLevel.LEVEL6`](/slides/python-net/cs/aspose.slides.export/compressionlevel/LEVEL6). |


### Viz také
* třída [`PptxOptions`](/slides/python-net/cs/aspose.slides.export/pptxoptions)
* třída [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)