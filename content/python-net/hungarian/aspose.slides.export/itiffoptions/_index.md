---
title: ITiffOptions class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.export/itiffoptions/
---
## ITiffOptions osztály

A TIFF formátumban történő prezentáció mentésének vezérlését szabályozó beállításokat biztosít.

Az ITiffOptions típus a következő tagokat tartalmazza:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`image_size`](/slides/python-net/hu/aspose.slides.export/itiffoptions/image_size/) | Meghatározza a generált TIFF kép méretét.<br/>            Alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a prezentáció dia méretétől fognak függni.<br/>            Olvasás/írás [`Size`](/slides/python-net/hu/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/hu/aspose.slides.export/itiffoptions/dpi_x/) | Meghatározza a vízszintes felbontást pont per hüvelykben.<br/>            Olvasás/írás **int**. |
| [`dpi_y`](/slides/python-net/hu/aspose.slides.export/itiffoptions/dpi_y/) | Meghatározza a függőleges felbontást pont per hüvelykben.<br/>            Olvasás/írás **int**. |
| [`show_hidden_slides`](/slides/python-net/hu/aspose.slides.export/itiffoptions/show_hidden_slides/) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem.<br/>            Alapértelmezett érték `false`. |
| [`compression_type`](/slides/python-net/hu/aspose.slides.export/itiffoptions/compression_type/) | Megadja a tömörítési típust.<br/>            Olvasás/írás [`TiffCompressionTypes`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/hu/aspose.slides.export/itiffoptions/pixel_format/) | Megadja a generált képek pixelformátumát.<br/>            Olvasás/írás [`ImagePixelFormat`](/slides/python-net/hu/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/hu/aspose.slides.export/itiffoptions/slides_layout_options/) | Megkapja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [`ISlidesLayoutOptions`](/slides/python-net/hu/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/hu/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Megadja a színes kép fekete-fehér képpé konvertálásának algoritmusát.<br/>            Ez a beállítás csak akkor kerül alkalmazásra, ha [`ITiffOptions.compression_type`](/slides/python-net/hu/aspose.slides.export/itiffoptions/compression_type) <br/>            [`TiffCompressionTypes.CCITT4`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes/CCITT4) vagy [`TiffCompressionTypes.CCITT3`](/slides/python-net/hu/aspose.slides.export/tiffcompressiontypes/CCITT3) értékre van állítva.<br/>            Olvasás/írás [`BlackWhiteConversionMode`](/slides/python-net/hu/aspose.slides.export/blackwhiteconversionmode).<br/>            Alapértelmezett érték [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/hu/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/hu/aspose.slides.export/itiffoptions/ink_options/) | Lehetővé teszi a tintaobjektumok megjelenését szabályozó beállítások megadását az exportált dokumentumban.<br/>            Csak olvasható [`IInkOptions`](/slides/python-net/hu/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)