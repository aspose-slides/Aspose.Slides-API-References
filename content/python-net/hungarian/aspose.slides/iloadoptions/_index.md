---
title: ILoadOptions class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/iloadoptions/
---
## ILoadOptions osztály

Lehetővé teszi további opciók (például formátum vagy alapértelmezett betűtípus) megadását a prezentáció betöltésekor.

Az ILoadOptions típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`load_format`](/slides/python-net/hu/aspose.slides/iloadoptions/load_format/) | Visszaadja vagy beállítja a betöltendő prezentáció formátumát.<br/>            Olvasás/írás [`LoadFormat`](/slides/python-net/hu/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides/iloadoptions/default_regular_font/) | Visszaadja vagy beállítja a szabványos betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található.<br/>            Olvasás/írás **str**. |
| [`default_symbol_font`](/slides/python-net/hu/aspose.slides/iloadoptions/default_symbol_font/) | Visszaadja vagy beállítja a szimbólum betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található.<br/>            Olvasás/írás **str**. |
| [`default_asian_font`](/slides/python-net/hu/aspose.slides/iloadoptions/default_asian_font/) | Visszaadja vagy beállítja az ázsiai betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található.<br/>            Olvasás/írás **str**. |
| [`password`](/slides/python-net/hu/aspose.slides/iloadoptions/password/) | Visszaadja vagy beállítja a jelszót.<br/>            Olvasás/írás **str**. |
| [`only_load_document_properties`](/slides/python-net/hu/aspose.slides/iloadoptions/only_load_document_properties/) | Ez a tulajdonság akkor értelmes, ha a prezentáció fájl jelszóval védett.<br/>            Az igaz érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni a titkosított <br/>            prezentáció fájlból, és a jelszót figyelmen kívül kell hagyni.<br/>            A hamis érték azt jelenti, hogy a teljes titkosított prezentációt be kell tölteni a megfelelő <br/>            jelszó használatával.<br/>            Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad.<br/>            Ha egy titkosított fájl dokumentum tulajdonságai nem nyilvánosak, és a tulajdonság értéke igaz, akkor<br/>            a dokumentum tulajdonságok nem tölthetők be, és kivétel keletkezik.<br/>            Olvasás/írás **bool**. |
| [`warning_callback`](/slides/python-net/hu/aspose.slides/iloadoptions/warning_callback/) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési <br/>            folyamat folytatódik-e vagy megszakad-e.<br/>            Olvasás/írás [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/hu/aspose.slides/iloadoptions/blob_management_options/) | Képviseli azokat a beállításokat, amelyeket a Binary Large Object (BLOB) kezelésének viselkedésére lehet használni,<br/>            például ideiglenes fájlok használata vagy a memória maximális BLOB bájt mérete. Ezek a beállítások arra szolgálnak, hogy a legjobb teljesítmény/ memóriafogyasztás arányt állítsák be egy adott környezet vagy követelmények számára.<br/>            A Binary Large Object (BLOB) egy bináris adat, amely egyetlen entitásként tárolódik – például a BLOB lehet <br/>            egy hang, videó vagy magának a prezentációnak a fájlja. |
| [`document_level_font_sources`](/slides/python-net/hu/aspose.slides/iloadoptions/document_level_font_sources/) | Meghatározza a külső betűtípusok forrásait, amelyeket a prezentáció használni fog.<br/>            Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztódnak meg más prezentációkkal |
| [`interruption_token`](/slides/python-net/hu/aspose.slides/iloadoptions/interruption_token/) | Az megszakítási kérések figyelésére szolgáló token.<br/>            <br/>            Ez a token kezeli a teljes [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) példány életciklusát. Bármely hosszú futású művelet, például a prezentáció <br/>            betöltése vagy mentése, megszakításra kerül a [`IInterruptionTokenSource.interrupt`](/slides/python-net/hu/aspose.slides/iinterruptiontokensource/interrupt) metódus meghívásával a <br/>            [`IInterruptionTokenSource`](/slides/python-net/hu/aspose.slides/iinterruptiontokensource)-ban. |
| [`resource_loading_callback`](/slides/python-net/hu/aspose.slides/iloadoptions/resource_loading_callback/) | Visszaadja vagy beállítja a visszahívási interfészt, amely kezeli a külső erőforrások betöltését.<br/>            Olvasás/írás [`IResourceLoadingCallback`](/slides/python-net/hu/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/hu/aspose.slides/iloadoptions/spreadsheet_options/) | Képviseli azokat a beállításokat, amelyeket további táblázatok viselkedésének meghatározására lehet használni. |
| [`default_text_language`](/slides/python-net/hu/aspose.slides/iloadoptions/default_text_language/) | Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét.<br/>            Olvasás/írás **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/hu/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése során.<br/>            <br/>A beágyazott bináris objektumok típusai:<br/><br/><br/>* VBA Projekt [`IPresentation.vba_project`](/slides/python-net/hu/aspose.slides/ipresentation/vba_project)<br/>* OLE Object beágyazott adat [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control bináris adat [`IControl.active_x_control_binary`](/slides/python-net/hu/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Olvasás/írás **bool**. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)