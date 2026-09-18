---
title: TiffOptions class
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.export/tiffoptions/
---
## TiffOptions osztály

Beállításokat biztosít, amelyek szabályozzák, hogyan mentődik egy prezentáció TIFF formátumban.

**Öröklés:**[`TiffOptions`](/slides/python-net/hu/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)

A TiffOptions típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.export/tiffoptions/__init__/#) | Alapértelmezett konstruktor. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/tiffoptions/warning_callback/) | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad.<br/>            Olvasás/írás [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/tiffoptions/progress_callback/) | Egy visszahívási objektumot képvisel a mentési folyamat előrehaladásának százalékos frissítéseihez.<br/>            Lásd [`IProgressCallback`](/slides/python-net/hu/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/tiffoptions/default_regular_font/) | Visszaadja vagy beállítja a használt betűtípust, ha a forrás betűtípusa nem található.<br/>            Olvasás/írás **str**. |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/tiffoptions/gradient_style/) | Visszaadja vagy beállítja a gradient vizuális stílusát.<br/>            Olvasás/írás [`GradientStyle`](/slides/python-net/hu/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/tiffoptions/skip_java_script_links/) | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hyperlinkeket. <br/>            Olvasás/írás **bool**. Az alapértelmezett érték **false**. |
| [`ink_options`](/slides/python-net/hu/aspose.slides.export/tiffoptions/ink_options/) | Lehetőségeket biztosít az exportált dokumentumban lévő Ink objektumok megjelenésének szabályozásához.<br/>            Csak olvasható [`IInkOptions`](/slides/python-net/hu/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/hu/aspose.slides.export/tiffoptions/show_hidden_slides/) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem.<br/>            Alapértelmezett érték `false`. |
| [`image_size`](/slides/python-net/hu/aspose.slides.export/tiffoptions/image_size/) | Megadja egy generált TIFF kép méretét.<br/>            Az alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a prezentáció dia méretétől lesznek kiszámítva.<br/>            Olvasás/írás **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/hu/aspose.slides.export/tiffoptions/dpi_x/) | Megadja a vízszintes felbontást pont per hüvelykben.<br/>            Olvasás/írás **int**. |
| [`dpi_y`](/slides/python-net/hu/aspose.slides.export/tiffoptions/dpi_y/) | Megadja a függőleges felbontást pont per hüvelykben.<br/>            Olvasás/írás **int**. |
| [`compression_type`](/slides/python-net/hu/aspose.slides.export/tiffoptions/compression_type/) | Megadja a tömörítés típusát.<br/>            Olvasás/írás [`TiffCompressionTypes`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/hu/aspose.slides.export/tiffoptions/pixel_format/) | Megadja a pixel formátumot a generált képekhez.<br/>            Olvasás/írás [`ImagePixelFormat`](/slides/python-net/hu/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/hu/aspose.slides.export/tiffoptions/slides_layout_options/) | Visszaadja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyeződnek a prezentáció exportálásakor [`ISlidesLayoutOptions`](/slides/python-net/hu/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/hu/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Megadja a színes kép fekete-fehér képpé konvertálásához használt algoritmust.<br/>            Ez az opció csak akkor kerül alkalmazásra, ha [`TiffOptions.compression_type`](/slides/python-net/hu/aspose.slides.export/tiffoptions/compression_type) <br/>            [`TiffCompressionTypes.CCITT4`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes/CCITT4) vagy [`TiffCompressionTypes.CCITT3`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes/CCITT3) értékre van állítva<br/>            Olvasás/írás [`BlackWhiteConversionMode`](/slides/python-net/hu/aspose.slides.export/blackwhiteconversionmode).<br/>            Alapértelmezett érték [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/hu/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |


### Lásd még
* osztály [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)
* osztály [`TiffOptions`](/slides/python-net/hu/aspose.slides.export/tiffoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)