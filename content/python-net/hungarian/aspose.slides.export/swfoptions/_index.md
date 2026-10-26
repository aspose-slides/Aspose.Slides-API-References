---
title: SwfOptions class
second_title: Aspose.Slides a Python számára .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.export/swfoptions/
---
## SwfOptions osztály

Opciókat biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció Swf formátumban.

**Öröklés:**[`SwfOptions`](/slides/python-net/hu/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)

A SwfOptions típus a következő tagokat teszi közzé:

## Konstruktorok

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.export/swfoptions/__init__/#) | Alapértelmezett konstruktor. |

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/swfoptions/warning_callback/) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad.<br/>            Olvasás/írás [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/swfoptions/progress_callback/) | Egy visszahívási objektumot képvisel a mentési előrehaladás százalékos frissítéseihez.<br/>            Lásd [`IProgressCallback`](/slides/python-net/hu/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/swfoptions/default_regular_font/) | Visszaadja vagy beállítja a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található.<br/>            Olvasás-írás **str**. |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/swfoptions/gradient_style/) | Visszaadja vagy beállítja a színátmenet vizuális stílusát.<br/>            Olvasás/írás [`GradientStyle`](/slides/python-net/hu/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/swfoptions/skip_java_script_links/) | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat.<br/>            Olvasás/írás **bool**. Az alapértelmezett érték **false** . |
| [`show_hidden_slides`](/slides/python-net/hu/aspose.slides.export/swfoptions/show_hidden_slides/) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diakat vagy sem.<br/>            Az alapértelmezett érték `false`. |
| [`compressed`](/slides/python-net/hu/aspose.slides.export/swfoptions/compressed/) | Megadja, hogy a generált SWF dokumentum legyen-e tömörítve vagy sem.<br/>            Az alapértelmezett érték `true`. |
| [`viewer_included`](/slides/python-net/hu/aspose.slides.export/swfoptions/viewer_included/) | Megadja, hogy a generált SWF dokumentum tartalmazza-e az integrált dokumentumnézőt vagy sem.<br/>            Az alapértelmezett érték `true`. |
| [`show_page_border`](/slides/python-net/hu/aspose.slides.export/swfoptions/show_page_border/) | Megadja, hogy a lapok körüli keret megjelenjen-e. Az alapértelmezett érték true. |
| [`show_full_screen`](/slides/python-net/hu/aspose.slides.export/swfoptions/show_full_screen/) | Teljes képernyős gomb megjelenítése/elrejtése. A flashvars-ban felülírható. Az alapértelmezett érték true. |
| [`show_page_stepper`](/slides/python-net/hu/aspose.slides.export/swfoptions/show_page_stepper/) | Oldal léptető megjelenítése/elrejtése. A flashvars-ban felülírható. Az alapértelmezett érték true. |
| [`show_search`](/slides/python-net/hu/aspose.slides.export/swfoptions/show_search/) | Keresési szakasz megjelenítése/elrejtése. A flashvars-ban felülírható. Az alapértelmezett érték true. |
| [`show_top_pane`](/slides/python-net/hu/aspose.slides.export/swfoptions/show_top_pane/) | Teljes felső panel megjelenítése/elrejtése. A flashvars-ban felülírható. Az alapértelmezett érték true. |
| [`show_bottom_pane`](/slides/python-net/hu/aspose.slides.export/swfoptions/show_bottom_pane/) | Alsó panel megjelenítése/elrejtése. A flashvars-ban felülírható. Az alapértelmezett érték true. |
| [`show_left_pane`](/slides/python-net/hu/aspose.slides.export/swfoptions/show_left_pane/) | Bal panel megjelenítése/elrejtése. A flashvars-ban felülírható. Az alapértelmezett érték true. |
| [`start_open_left_pane`](/slides/python-net/hu/aspose.slides.export/swfoptions/start_open_left_pane/) | Bal panel nyitott állapotú indítása. A flashvars-ban felülírható. Az alapértelmezett érték false. |
| [`enable_context_menu`](/slides/python-net/hu/aspose.slides.export/swfoptions/enable_context_menu/) | Helyi menü engedélyezése/letiltása. Az alapértelmezett érték true. |
| [`logo_image_bytes`](/slides/python-net/hu/aspose.slides.export/swfoptions/logo_image_bytes/) | A kép, amely a néző jobb felső sarkában logóként jelenik meg.<br/>            A képfájlnak 32×64 pixel méretű PNG-nek kell lennie, ellenkező esetben a logó helytelenül jelenhet meg. |
| [`logo_link`](/slides/python-net/hu/aspose.slides.export/swfoptions/logo_link/) | Visszaadja vagy beállítja a logó teljes hiperhivatkozási címét.<br/>            Csak akkor van hatása, ha egy [`SwfOptions.logo_image_bytes`](/slides/python-net/hu/aspose.slides.export/swfoptions/logo_image_bytes) van megadva. |
| [`jpeg_quality`](/slides/python-net/hu/aspose.slides.export/swfoptions/jpeg_quality/) | Megadja a JPEG képek minőségét.<br/>            Az alapértelmezett érték 95. |
| [`slides_layout_options`](/slides/python-net/hu/aspose.slides.export/swfoptions/slides_layout_options/) | Visszaadja vagy beállítja azt a módot, amelyben a diákat az oldalon elhelyezik egy [`ISlidesLayoutOptions`](/slides/python-net/hu/aspose.slides.export/islideslayoutoptions) prezentáció exportálásakor.<br/>            Ez a tulajdonság nem támogatja [`HandoutLayoutingOptions`](/slides/python-net/hu/aspose.slides.export/handoutlayoutingoptions) típusú objektumok hozzárendelését. |

### Lásd még
* osztály [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)
* osztály [`SwfOptions`](/slides/python-net/hu/aspose.slides.export/swfoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)