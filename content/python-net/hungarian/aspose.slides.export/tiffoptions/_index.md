---
title: TiffOptions class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.export/tiffoptions/
---
## TiffOptions osztály

Olyan beállításokat biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció TIFF formátumban.

**Öröklés:**[`TiffOptions`](/slides/python-net/hu/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)

A TiffOptions típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.export/tiffoptions/__init__/#) | Alapértelmezett konstruktor. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/tiffoptions/warning_callback/) | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon.<br/>            Olvasás/írás [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/tiffoptions/progress_callback/) | Egy visszahívási objektumot képvisel a mentési előrehaladás százalékos frissítéseihez.<br/>            Lásd [`IProgressCallback`](/slides/python-net/hu/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/tiffoptions/default_regular_font/) | Visszaadja vagy beállítja a betűtípust, amelyet akkor használ, ha a forrásbetűtípus nem található.<br/>            Olvasás/írás **str**. |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/tiffoptions/gradient_style/) | Visszaadja vagy beállítja a fokozat vizuális stílusát.<br/>            Olvasás/írás [`GradientStyle`](/slides/python-net/hu/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/tiffoptions/skip_java_script_links/) | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat.<br/>            Olvasás/írás **bool**. Az alapértelmezett érték **false**. |
| [`ink_options`](/slides/python-net/hu/aspose.slides.export/tiffoptions/ink_options/) | Olyan lehetőségeket biztosít, amelyek szabályozzák a tintatárgyak megjelenését az exportált dokumentumban.<br/>            Csak olvasás [`IInkOptions`](/slides/python-net/hu/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/hu/aspose.slides.export/tiffoptions/show_hidden_slides/) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem.<br/>            Az alapértelmezett érték `false`. |
| [`image_size`](/slides/python-net/hu/aspose.slides.export/tiffoptions/image_size/) | Megadja egy generált TIFF kép méretét.<br/>            Az alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a prezentáció diákméretének értéke alapján lesznek kiszámítva.<br/>            Olvasás/írás [`Size`](/slides/python-net/hu/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/hu/aspose.slides.export/tiffoptions/dpi_x/) | Megadja a vízszintes felbontást pont per hüvelykben.<br/>            Olvasás/írás **int**. |
| [`dpi_y`](/slides/python-net/hu/aspose.slides.export/tiffoptions/dpi_y/) | Megadja a függőleges felbontást pont per hüvelykben.<br/>            Olvasás/írás **int**. |
| [`compression_type`](/slides/python-net/hu/aspose.slides.export/tiffoptions/compression_type/) | Megadja a tömörítési típust.<br/>            Olvasás/írás [`TiffCompressionTypes`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/hu/aspose.slides.export/tiffoptions/pixel_format/) | Megadja a pixelformátumot a generált képekhez.<br/>            Olvasás/írás [`ImagePixelFormat`](/slides/python-net/hu/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/hu/aspose.slides.export/tiffoptions/slides_layout_options/) | Lekéri vagy beállítja azt a módot, ahogy a diák elhelyezésre kerülnek az oldalon a prezentáció exportálásakor [`ISlidesLayoutOptions`](/slides/python-net/hu/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/hu/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Megadja a színes kép fekete-fehér képpé konvertálásának algoritmusát.<br/>            Ez az opció csak akkor lesz alkalmazva, ha [`TiffOptions.compression_type`](/slides/python-net/hu/aspose.slides.export/tiffoptions/compression_type)<br/>            [`TiffCompressionTypes.CCITT4`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes/CCITT4) vagy [`TiffCompressionTypes.CCITT3`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes/CCITT3) értékre van beállítva<br/>            Olvasás/írás [`BlackWhiteConversionMode`](/slides/python-net/hu/aspose.slides.export/blackwhiteconversionmode).<br/>            Az alapértelmezett érték [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/hu/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Lásd még
* osztály [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)
* osztály [`TiffOptions`](/slides/python-net/hu/aspose.slides.export/tiffoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)