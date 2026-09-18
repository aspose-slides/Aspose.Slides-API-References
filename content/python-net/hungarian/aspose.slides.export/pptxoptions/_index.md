---
title: PptxOptions class
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.export/pptxoptions/
---
## PptxOptions osztály

Represents options for saving OpenXml presentations (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

**Öröklés:**[`PptxOptions`](/slides/python-net/hu/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)

The PptxOptions type exposes the following members:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.export/pptxoptions/__init__/#) | Új példányt hoz létre a PptxOptions-ból |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/pptxoptions/warning_callback/) | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad.<br/>            Read/write [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/pptxoptions/progress_callback/) | Egy visszahívási objektumot képvisel a mentés előrehaladási frissítéseihez százalékban.<br/>            Lásd [`IProgressCallback`](/slides/python-net/hu/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/pptxoptions/default_regular_font/) | Visszaadja vagy beállítja a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/pptxoptions/gradient_style/) | Visszaadja vagy beállítja a színátmenet vizuális stílusát.<br/>            Read/write [`GradientStyle`](/slides/python-net/hu/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/pptxoptions/skip_java_script_links/) | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat.<br/>            Read/write **bool**. Az alapértelmezett érték **false**. |
| [`conformance`](/slides/python-net/hu/aspose.slides.export/pptxoptions/conformance/) | Megadja azt a kompatibilitási osztályt, amelynek a Presentation dokumentum megfelel.<br/>            Alapértelmezett érték [`Conformance.ECMA_376_2006`](/slides/python-net/hu/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/hu/aspose.slides.export/pptxoptions/zip_64_mode/) | Megadja, hogy a ZIP64 formátumot használja-e a Presentation dokumentum.<br/>            Az alapértelmezett érték [`Zip64Mode.IF_NECESSARY`](/slides/python-net/hu/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/hu/aspose.slides.export/pptxoptions/refresh_thumbnail/) | Megadja, hogy a prezentáció miniatűr frissül-e.<br/>            Read/write **bool**.<br/>            Alapértelmezett érték **true**. |
| [`compression_level`](/slides/python-net/hu/aspose.slides.export/pptxoptions/compression_level/) | Megadja a prezentáció dokumentum mentésekor használt tömörítési szintet.<br/>            Az alapértelmezett érték [`CompressionLevel.LEVEL6`](/slides/python-net/hu/aspose.slides.export/compressionlevel/LEVEL6). |


### Lásd még
* osztály [`PptxOptions`](/slides/python-net/hu/aspose.slides.export/pptxoptions)
* osztály [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)