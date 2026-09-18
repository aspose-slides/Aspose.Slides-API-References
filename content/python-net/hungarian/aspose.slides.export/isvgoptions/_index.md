---
title: ISVGOptions class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.export/isvgoptions/
---
## ISVGOptions osztály

SVG opciókat képvisel.

Az ISVGOptions típus a következő tagokat teszi közzé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/hu/aspose.slides.export/isvgoptions/vectorize_text/) | Meghatározza, hogy a dián lévő szöveg grafikusként legyen-e mentve.<br/>            Olvasás/írás **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/hu/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Visszaadja vagy beállítja az alacsony felbontású határt a metafájl rasterizálásához.<br/>            Olvasás/írás **int**. |
| [`disable_3d_text`](/slides/python-net/hu/aspose.slides.export/isvgoptions/disable_3d_text/) | Meghatározza, hogy a 3D szöveg le legyen-e tiltva az SVG-ben.<br/>            Olvasás/írás **bool**. |
| [`disable_gradient_split`](/slides/python-net/hu/aspose.slides.export/isvgoptions/disable_gradient_split/) | Letiltja a FromCornerX és FromCenter gradientek felosztását.<br/>            Olvasás/írás **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/hu/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | Az SVG 1.1 nem támogatja a jelölők belső margóinak meghatározását.<br/>            Az Aspose.Slides SVG írómotor megoldást kínál erre a problémára:<br/>            levágja a nyíllal végződő vonal végét, így a vonal nem fed át a jelölőket.<br/>            Ez a beállítás kikapcsolja ezt a viselkedést.<br/>            Olvasás/írás **bool**. |
| [`jpeg_quality`](/slides/python-net/hu/aspose.slides.export/isvgoptions/jpeg_quality/) | Meghatározza a JPEG kódolás minőségét.<br/>            Olvasás/írás **int**. |
| [`shape_formatting_controller`](/slides/python-net/hu/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Visszaad és beállít egy callback interfészt, amely lehetővé teszi a felhasználó számára a forma átalakításának vezérlését.<br/>            Olvasás/írás [`ISvgShapeFormattingController`](/slides/python-net/hu/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/hu/aspose.slides.export/isvgoptions/pictures_compression/) | A képek tömörítési szintjét képviseli<br/>            Olvasás/írás [`ISVGOptions.pictures_compression`](/slides/python-net/hu/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/hu/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Egy logikai jelző, amely azt mutatja, hogy a levágott részek a dokumentum részeként maradjanak-e. Ha true, a levágott <br/>            részek eltávolításra kerülnek, ha false, akkor a dokumentumban lesznek sorosítva (ami nagyobb fájlméretet eredményezhet)<br/>            Olvasás/írás **bool**. |
| [`use_frame_size`](/slides/python-net/hu/aspose.slides.export/isvgoptions/use_frame_size/) | Meghatározza, hogy a szövegkeret szerepeljen-e a renderelési területen vagy sem.<br/>            Olvasás/írás **bool**.<br/>            Az alapértelmezett érték false. |
| [`use_frame_rotation`](/slides/python-net/hu/aspose.slides.export/isvgoptions/use_frame_rotation/) | Meghatározza, hogy a forma megadott forgatását végrehajtsa-e a renderelés során vagy sem.<br/>            Olvasás/írás **bool**.<br/>            Az alapértelmezett érték true. |
| [`external_fonts_handling`](/slides/python-net/hu/aspose.slides.export/isvgoptions/external_fonts_handling/) | Meghatározza a külsőleg betöltött betűtípusok kezelésének módját.<br/>            Olvasás/írás [`SvgExternalFontsHandling`](/slides/python-net/hu/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/hu/aspose.slides.export/isvgoptions/ink_options/) | Olyan beállításokat biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban.<br/>            Csak olvasás [`IInkOptions`](/slides/python-net/hu/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/hu/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Egy értéket ad vissza vagy állít be, amely meghatározza, hogy a szöveget ligatúrák használata nélkül rendereljék-e.<br/>            Ha `true`-ra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság **false**. |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)