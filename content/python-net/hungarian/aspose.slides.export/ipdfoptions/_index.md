---
title: IPdfOptions class
second_title: Aspose.Slides a Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.export/ipdfoptions/
---
## IPdfOptions osztály

Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció PDF formátumban.

Az IPdfOptions típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/text_compression/) | Megadja a tömörítési típust, amely a dokumentum összes szöveges tartalmára lesz alkalmazva.<br/>            Olvasás/írás [`PdfTextCompression`](/slides/python-net/hu/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Jelzi, hogy a legjobb tömörítést (az alapértelmezett helyett) kell-e kiválasztani minden képhez automatikusan.<br/>            Ha **bool**.true értékre van állítva, minden prezentációs képnél a legmegfelelőbb tömörítési algoritmus lesz kiválasztva, ami a kész PDF-dokumentum kisebb méretéhez vezet.<br/>            A legjobb kép-tömörítési arány kiválasztása számításigényes, további RAM-ot igényel, és ez az opció alapértelmezésben **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | Igaz, ha a 32-127 tartományú ASCII karakterekhez true type betűtípusokat kell beágyazni.<br/>            A 127-nél nagyobb karakterkódokhoz tartozó betűtípusok mindig beágyazottak.<br/>            Olvasás/írás **bool**. |
| [`show_hidden_slides`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Megadja, hogy a generált dokumentum tartalmazza-e a rejtett diákot vagy sem.<br/>            Alapértelmezett érték `false`. |
| [`additional_common_font_families`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Visszaadja vagy beállítja a felhasználó által meghatározott betűcsalád-nevek tömbjét, amelyeket az Aspose.Slides közösnek tekint.<br/>            Olvasás/írás **str**[]. |
| [`embed_full_fonts`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Meghatározza, hogy a betűtípus minden karaktere be legyen ágyazva, vagy csak a használt részhalmaz.<br/>            Olvasás/írás **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Jelzi, hogy a szöveget bitmapképpé rasterizálni kell-e és PDF-be menteni, ha a betűtípus nem támogatja a félkövér formázást.<br/>            Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét a kész PDF-ben.<br/>            Olvasás/írás **bool**. |
| [`jpeg_quality`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/jpeg_quality/) | Visszaadja vagy beállítja a PDF-dokumentumban lévő JPEG képek minőségét meghatározó értéket.<br/>            Olvasás/írás **int**. |
| [`compliance`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/compliance/) | A létrehozott PDF-dokumentum kívánt megfelelőségi szintje.<br/>            Olvasás/írás [`PdfCompliance`](/slides/python-net/hu/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/password/) | Felhasználói jelszó beállítása a PDF-dokumentum védelméhez. <br/>            Olvasás/írás **str**. |
| [`access_permissions`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/access_permissions/) | Tartalmaz egy zászlóhalmazt, amely megadja, hogy milyen hozzáférési jogosultságok legyenek megadva a dokumentum felhasználói hozzáféréssel való megnyitásakor.<br/>            Lásd [`PdfAccessPermissions`](/slides/python-net/hu/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | Igaz, ha a prezentációban használt összes metafájl PNG képekké konvertálódik.<br/>            Olvasás/írás **bool**. |
| [`sufficient_resolution`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Visszaadja vagy beállítja a PDF-dokumentumban lévő képek felbontását meghatározó értéket.<br/>            <br/>A tulajdonság befolyásolja a fájl méretét, az exportálás időt és a kép minőségét.<br/><br/><br/>Az alapértelmezett érték **96** .<br/><br/><br/>            Olvasás/írás **float**. |
| [`draw_slides_frame`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/draw_slides_frame/) | Igaz, ha minden dia köré fekete keretet rajzol.<br/>             Olvasás/írás **bool**. |
| [`slides_layout_options`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/slides_layout_options/) | Lekéri vagy beállítja azt a módot, amelyben a diák az oldalon elhelyezésre kerülnek a prezentáció exportálásakor [`ISlidesLayoutOptions`](/slides/python-net/hu/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/image_transparent_color/) | Lekéri vagy beállítja a kép átlátszó színét. |
| [`apply_image_transparent`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Alkalmazza a megadott átlátszó színt a képre, ha `true`. |
| [`ink_options`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/ink_options/) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban.<br/>            Csak olvasás [`IInkOptions`](/slides/python-net/hu/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/include_ole_data/) | Igaz, ha a prezentációból származó összes OLE adat a kész PDF-ben beágyazott fájlokká konvertálódik.<br/>            Olvasás/írás **bool**. |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)