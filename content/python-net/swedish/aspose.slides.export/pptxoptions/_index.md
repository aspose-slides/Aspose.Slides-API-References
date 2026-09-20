---
title: PptxOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/pptxoptions/
---
## PptxOptions klass

Representerar alternativ för att spara OpenXml-presentationer (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

**Inheritance:**[`PptxOptions`](/slides/python-net/sv/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)

PptxOptions-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.export/pptxoptions/__init__/#) | Skapar en ny instans av PptxOptions |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`warning_callback`](/slides/python-net/sv/aspose.slides.export/pptxoptions/warning_callback/) | Returnerar eller sätter ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas.<br/>            Läs/skriv [`IWarningCallback`](/slides/python-net/sv/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/sv/aspose.slides.export/pptxoptions/progress_callback/) | Representerar ett återanrop-objekt för sparande av förloppsuppdateringar i procent.<br/>            Se [`IProgressCallback`](/slides/python-net/sv/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/sv/aspose.slides.export/pptxoptions/default_regular_font/) | Returnerar eller sätter teckensnitt som används om källteckensnittet inte hittas.<br/>            Läs-skriv **str**. |
| [`gradient_style`](/slides/python-net/sv/aspose.slides.export/pptxoptions/gradient_style/) | Returnerar eller sätter den visuella stilen för gradienten.<br/>            Läs/skriv [`GradientStyle`](/slides/python-net/sv/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/sv/aspose.slides.export/pptxoptions/skip_java_script_links/) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. <br/>            Läs/skriv **bool**. Standardvärdet är **false** . |
| [`conformance`](/slides/python-net/sv/aspose.slides.export/pptxoptions/conformance/) | Anger den efterlevnadsklass som Presentation-dokumentet följer.<br/>            Standardvärdet är [`Conformance.ECMA_376_2006`](/slides/python-net/sv/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/sv/aspose.slides.export/pptxoptions/zip_64_mode/) | Anger om ZIP64-formatet används för Presentation-dokumentet. <br/>            Standardvärdet är [`Zip64Mode.IF_NECESSARY`](/slides/python-net/sv/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/sv/aspose.slides.export/pptxoptions/refresh_thumbnail/) | Anger om presentations-miniatyrbilden ska uppdateras. <br/>            Läs/skriv **bool**.<br/>            Standardvärdet är **true** . |
| [`compression_level`](/slides/python-net/sv/aspose.slides.export/pptxoptions/compression_level/) | Anger komprimeringsnivån som används när presentations-dokumentet sparas.<br/>            Standardvärdet är [`CompressionLevel.LEVEL6`](/slides/python-net/sv/aspose.slides.export/compressionlevel/LEVEL6). |


### Se även
* klass [`PptxOptions`](/slides/python-net/sv/aspose.slides.export/pptxoptions)
* klass [`SaveOptions`](/slides/python-net/sv/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)