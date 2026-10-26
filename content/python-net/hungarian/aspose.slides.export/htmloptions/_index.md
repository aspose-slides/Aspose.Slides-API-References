---
title: HtmlOptions class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.export/htmloptions/
---
## HtmlOptions osztály

HTML exportálási beállításokat reprezentál.

**Öröklés:**[`HtmlOptions`](/slides/python-net/hu/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)

A HtmlOptions típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/hu/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Létrehozza az új HtmlOptions objektumot, amely visszahívást ad meg. |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.export/htmloptions/__init__/#) | Létrehozza az új HtmlOptions objektumot egyetlen HTML fájlba mentéshez. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/htmloptions/warning_callback/) | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad.<br/>            Olvasás/írás [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/htmloptions/progress_callback/) | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban jelzi.<br/>            Lásd [`IProgressCallback`](/slides/python-net/hu/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/htmloptions/default_regular_font/) | Visszaad vagy beállít egy betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található.<br/>            Olvasás-írás **str**. |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/htmloptions/gradient_style/) | Visszaad vagy beállít a gradient vizuális stílusát.<br/>            Olvasás/írás [`GradientStyle`](/slides/python-net/hu/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/htmloptions/skip_java_script_links/) | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat.<br/>            Olvasás/írás **bool**. Az alapértelmezett érték **false** . |
| [`slides_layout_options`](/slides/python-net/hu/aspose.slides.export/htmloptions/slides_layout_options/) | Megkapja vagy beállítja azt a módot, amelyben a diák az oldalon elhelyezésre kerülnek a prezentáció exportálásakor [`ISlidesLayoutOptions`](/slides/python-net/hu/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/hu/aspose.slides.export/htmloptions/ink_options/) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban.<br/>            Írásvédett [`IInkOptions`](/slides/python-net/hu/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/hu/aspose.slides.export/htmloptions/show_hidden_slides/) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem.<br/>            Alapértelmezés szerint `false`. |
| [`html_formatter`](/slides/python-net/hu/aspose.slides.export/htmloptions/html_formatter/) | Visszaad vagy beállít HTML sablont.<br/>            Olvasás/írás [`IHtmlFormatter`](/slides/python-net/hu/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/hu/aspose.slides.export/htmloptions/disable_font_ligatures/) | Megkapja vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül legyen-e megjelenítve.<br/>            Ha `true`-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság `false`. |
| [`slide_image_format`](/slides/python-net/hu/aspose.slides.export/htmloptions/slide_image_format/) | Visszaad vagy beállít dia képformátum opciókat.<br/>            Olvasás/írás [`ISlideImageFormat`](/slides/python-net/hu/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/hu/aspose.slides.export/htmloptions/jpeg_quality/) | Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban.<br/>            Olvasás/írás **int**. |
| [`pictures_compression`](/slides/python-net/hu/aspose.slides.export/htmloptions/pictures_compression/) | A képek tömörítési szintjét képviseli |
| [`delete_pictures_cropped_areas`](/slides/python-net/hu/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Egy logikai jelző jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. Ha true, a levágott <br/>            részek eltávolításra kerülnek, ha false, akkor a dokumentumban sorosítva lesznek (ami esetleg nagyobb fájlhoz vezethet) |
| [`svg_responsive_layout`](/slides/python-net/hu/aspose.slides.export/htmloptions/svg_responsive_layout/) | True, ha a szélesség és magasság attribútumokat ki akarja zárni az svg konténerből – ez reszponzív elrendezést eredményez. False, egyébként.<br/>            Olvasás/írás **bool**. |

### Lásd még
* osztály [`HtmlOptions`](/slides/python-net/hu/aspose.slides.export/htmloptions)
* osztály [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)