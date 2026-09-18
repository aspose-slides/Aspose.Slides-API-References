---
title: SVGOptions class
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.export/svgoptions/
---
## SVGOptions osztály

Az SVGOptions opciókat képviseli.

**Inheritance:**[`SVGOptions`](/slides/python-net/hu/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)

Az SVGOptions típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.export/svgoptions/__init__/#) | Új példányt hoz létre az SVGOptions osztályból. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/hu/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Új példányt hoz létre az SVGOptions osztályból, megadva a link beágyazó vezérlő objektumot. |

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/svgoptions/warning_callback/) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad.<br/>            Olvasás/írás [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/svgoptions/progress_callback/) | Egy visszahívási objektumot képvisel a mentési előrehaladási frissítések százalékos megjelenítéséhez.<br/>            Lásd [`IProgressCallback`](/slides/python-net/hu/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/svgoptions/default_regular_font/) | Visszaadja vagy beállítja a betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található.<br/>            Olvasás-írás **str**. |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/svgoptions/gradient_style/) | Visszaadja vagy beállítja a gradiens vizuális stílusát.<br/>            Olvasás/írás [`GradientStyle`](/slides/python-net/hu/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/svgoptions/skip_java_script_links/) | Meghatározza, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokkal rendelkező hiperhivatkozásokat.<br/>            Olvasás/írás **bool**. Az alapértelmezett érték **false**. |
| [`ink_options`](/slides/python-net/hu/aspose.slides.export/svgoptions/ink_options/) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban.<br/>            Csak olvasható [`IInkOptions`](/slides/python-net/hu/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/hu/aspose.slides.export/svgoptions/use_frame_size/) | Meghatározza, hogy a szövegkeret szerepel-e a renderelési területen vagy sem.<br/>            Olvasás/írás **bool**.<br/>            Alapértelmezett érték false. |
| [`use_frame_rotation`](/slides/python-net/hu/aspose.slides.export/svgoptions/use_frame_rotation/) | Meghatározza, hogy a renderelés során elvégezi-e a megadott forgatást a alakzaton vagy sem.<br/>            Olvasás/írás **bool**.<br/>            Alapértelmezett érték true. |
| [`vectorize_text`](/slides/python-net/hu/aspose.slides.export/svgoptions/vectorize_text/) | Meghatározza, hogy a dián lévő szöveg grafikai elemként legyen-e mentve.<br/>            Olvasás/írás **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/hu/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Visszaadja vagy beállítja a metafájl raszterizálásának alsó felbontási határát.<br/>            Olvasás/írás **int**. |
| [`disable_3d_text`](/slides/python-net/hu/aspose.slides.export/svgoptions/disable_3d_text/) | Meghatározza, hogy a 3D szöveg le van-e tiltva az SVG-ben.<br/>            Olvasás/írás **bool**. |
| [`disable_gradient_split`](/slides/python-net/hu/aspose.slides.export/svgoptions/disable_gradient_split/) | Letiltja a FromCornerX és FromCenter gradiens felbontását.<br/>            Olvasás/írás **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/hu/aspose.slides.export/svgoptions/disable_line_end_cropping/) | Az SVG 1.1 nem rendelkezik képességgel a jelölők belső távolságának meghatározására.<br/>            Az Aspose.Slides SVG író motor megoldást kínál erre a problémára:<br/>            levágja a nyíllal ellátott vonal végét, így a vonal nem fed felül a jelölőket.<br/>            Ez a beállítás kikapcsolja ezt a viselkedést.<br/>            Olvasás/írás **bool**. |
| [`default`](/slides/python-net/hu/aspose.slides.export/svgoptions/default/) | Visszaadja az alapértelmezett beállításokat.<br/>            Csak olvasható [`SVGOptions`](/slides/python-net/hu/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/hu/aspose.slides.export/svgoptions/simple/) | Visszaadja a legegyszerűbb és legkisebb SVG fájl generálásához szükséges beállításokat.<br/>            Csak olvasható [`SVGOptions`](/slides/python-net/hu/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/hu/aspose.slides.export/svgoptions/wysiwyg/) | Visszaadja a legpontosabb SVG fájl generálásához szükséges beállításokat.<br/>            Csak olvasható [`SVGOptions`](/slides/python-net/hu/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/hu/aspose.slides.export/svgoptions/jpeg_quality/) | Meghatározza a JPEG kódolási minőséget.<br/>            Olvasás/írás **int**. |
| [`shape_formatting_controller`](/slides/python-net/hu/aspose.slides.export/svgoptions/shape_formatting_controller/) | Visszaadja és beállítja a visszahívási felületet, amely lehetővé teszi a felhasználó számára az alakzat átalakításának irányítását.<br/>            Olvasás/írás [`ISvgShapeFormattingController`](/slides/python-net/hu/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/hu/aspose.slides.export/svgoptions/pictures_compression/) | A képek tömörítési szintjét képviseli |
| [`delete_pictures_cropped_areas`](/slides/python-net/hu/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Egy boolean jelző, amely jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. Ha igaz, a levágott <br/>            részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban lesznek sorosítva (ami esetleg nagyobb fájlhoz vezethet) |
| [`external_fonts_handling`](/slides/python-net/hu/aspose.slides.export/svgoptions/external_fonts_handling/) | Meghatározza a külsőleg betöltött betűtípusok kezelésének módját.<br/>            Olvasás/írás [`SvgExternalFontsHandling`](/slides/python-net/hu/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/hu/aspose.slides.export/svgoptions/disable_font_ligatures/) | Visszaadja vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül legyen-e renderelve.<br/>            Ha `true`-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság `false`. |

### Lásd még
* osztály [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)
* osztály [`SVGOptions`](/slides/python-net/hu/aspose.slides.export/svgoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)