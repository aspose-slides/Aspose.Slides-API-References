---
title: RenderingOptions class
second_title: Aspose.Slides a Python számára .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.export/renderingoptions/
---
## RenderingOptions osztály

Lehetőségeket biztosít, amelyek szabályozzák, hogyan renderelődik egy prezentáció/diák.

**Öröklés:**[`RenderingOptions`](/slides/python-net/hu/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)

A RenderingOptions típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.export/renderingoptions/__init__/#) | Alapértelmezett konstruktor. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/renderingoptions/warning_callback/) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad.<br/>            Olvasás/írás [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/renderingoptions/progress_callback/) | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban jelzi.<br/>            Lásd [`IProgressCallback`](/slides/python-net/hu/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/renderingoptions/default_regular_font/) | Visszaadja vagy beállítja a forrás betűtípus nem található esetén használt betűtípust.<br/>            Olvasás/írás **str**. |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/renderingoptions/gradient_style/) | Visszaadja vagy beállítja a gradient vizuális stílusát.<br/>            Olvasás/írás [`GradientStyle`](/slides/python-net/hu/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/renderingoptions/skip_java_script_links/) | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat.<br/>            Olvasás/írás **bool**. Az alapértelmezett érték **false**. |
| [`slides_layout_options`](/slides/python-net/hu/aspose.slides.export/renderingoptions/slides_layout_options/) | Megkapja vagy beállítja a módot, amelyben a diák az oldalon elhelyezésre kerülnek a prezentáció exportálásakor [`ISlidesLayoutOptions`](/slides/python-net/hu/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/hu/aspose.slides.export/renderingoptions/ink_options/) | Lehetőségeket biztosít, amelyek szabályozzák a tinta objektumok megjelenését az exportált dokumentumban.<br/>            Csak-olvasás [`IInkOptions`](/slides/python-net/hu/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/hu/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Megkapja vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre.<br/>            Ha `true` értékre van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság `false` értékre van állítva. |

### Lásd még
* osztály [`RenderingOptions`](/slides/python-net/hu/aspose.slides.export/renderingoptions)
* osztály [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)