---
title: ITiffOptions class
second_title: Aspose.Slides a Python számára a .NET API hivatkozásból
description: 
type: docs
url: /hu/aspose.slides.export/itiffoptions/
---
## ITiffOptions osztály

Lehetőségeket biztosít, amelyek szabályozzák, hogyan kerül mentésre egy prezentáció TIFF formátumban.

Az ITiffOptions típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`image_size`](/slides/python-net/hu/aspose.slides.export/itiffoptions/image_size/) | Megadja a létrehozott TIFF kép méretét.<br/>            Alapértelmezett érték 0x0, ami azt jelenti, hogy a kép méretei a prezentáció dia méretértéke alapján kerülnek kiszámításra.<br/>            Olvasás/írás **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/hu/aspose.slides.export/itiffoptions/dpi_x/) | Megadja a vízszintes felbontást pont per hüvelykben.<br/>            Olvasás/írás **int**. |
| [`dpi_y`](/slides/python-net/hu/aspose.slides.export/itiffoptions/dpi_y/) | Megadja a függőleges felbontást pont per hüvelykben.<br/>            Olvasás/írás **int**. |
| [`show_hidden_slides`](/slides/python-net/hu/aspose.slides.export/itiffoptions/show_hidden_slides/) | Megadja, hogy a létrehozott dokumentum tartalmazzon-e rejtett diákat vagy sem.<br/>            Alapértelmezett érték `false`. |
| [`compression_type`](/slides/python-net/hu/aspose.slides.export/itiffoptions/compression_type/) | Megadja a tömörítés típusát.<br/>            Olvasás/írás [`TiffCompressionTypes`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/hu/aspose.slides.export/itiffoptions/pixel_format/) | Megadja a létrehozott képek pixelformátumát.<br/>            Olvasás/írás [`ImagePixelFormat`](/slides/python-net/hu/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/hu/aspose.slides.export/itiffoptions/slides_layout_options/) | Lekérdezi vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek egy prezentáció [`ISlidesLayoutOptions`](/slides/python-net/hu/aspose.slides.export/islideslayoutoptions) exportálásakor. |
| [`bw_conversion_mode`](/slides/python-net/hu/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Megadja a színes kép fekete-fehér képpé konvertálásának algoritmusát.<br/>            Ez az opció csak akkor lesz alkalmazva, ha [`ITiffOptions.compression_type`](/slides/python-net/hu/aspose.slides.export/itiffoptions/compression_type) <br/>            [`TiffCompressionTypes.CCITT4`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes/CCITT4) vagy [`TiffCompressionTypes.CCITT3`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes/CCITT3) értékre van beállítva<br/>            Olvasás/írás [`BlackWhiteConversionMode`](/slides/python-net/hu/aspose.slides.export/blackwhiteconversionmode).<br/>            Alapértelmezett érték [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/hu/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/hu/aspose.slides.export/itiffoptions/ink_options/) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban.<br/>            Csak olvasható [`IInkOptions`](/slides/python-net/hu/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)