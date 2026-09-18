---
title: LoadOptions class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/loadoptions/
---
## LoadOptions osztály

Lehetővé teszi további beállítások (például formátum vagy alapértelmezett betűtípus) megadását a bemutató betöltésekor.

A LoadOptions típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/loadoptions/__init__/#) | Creates new default load options. |
| [`__init__(self, load_format)`](/slides/python-net/hu/aspose.slides/loadoptions/__init__/#loadformat) | Creates new load options. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`load_format`](/slides/python-net/hu/aspose.slides/loadoptions/load_format/) | Visszaadja vagy beállítja a betöltendő bemutató formátumát.<br/>            Read/write [`LoadFormat`](/slides/python-net/hu/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides/loadoptions/default_regular_font/) | Visszaadja vagy beállítja a szabványos betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található.<br/>            Read/write **str**. |
| [`default_symbol_font`](/slides/python-net/hu/aspose.slides/loadoptions/default_symbol_font/) | Visszaadja vagy beállítja a szimbólum betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található.<br/>            Read/write **str**. |
| [`default_asian_font`](/slides/python-net/hu/aspose.slides/loadoptions/default_asian_font/) | Visszaadja vagy beállítja az ázsiai betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található.<br/>            Read/write **str**. |
| [`password`](/slides/python-net/hu/aspose.slides/loadoptions/password/) | Lekérdezi vagy beállítja a jelszót.<br/>            Read/write **str**. |
| [`only_load_document_properties`](/slides/python-net/hu/aspose.slides/loadoptions/only_load_document_properties/) | Ez a tulajdonság akkor értelmes, ha a bemutató fájl jelszóval védett.<br/>            A true érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni egy titkosított bemutató fájlból, és a jelszót figyelmen kívül kell hagyni.<br/>            A false érték azt jelenti, hogy a teljes titkosított bemutatót a megfelelő jelszó használatával kell betölteni.<br/>            Ha a bemutató nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad.<br/>            Ha egy titkosított fájl dokumentum tulajdonságai nem nyilvánosak, és a tulajdonság értéke true, akkor a dokumentum tulajdonságok betöltése nem lehetséges, és kivétel lesz dobva.<br/>            Read/write **bool**. |
| [`warning_callback`](/slides/python-net/hu/aspose.slides/loadoptions/warning_callback/) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad.<br/>            Read/write [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/hu/aspose.slides/loadoptions/blob_management_options/) | A lehetőségek, amelyek a Binary Large Object (BLOB) kezelésének viselkedését szabályozhatják,<br/>            például ideiglenes fájlok használata vagy a memória BLOB-ok maximális mérete. Ezek a beállítások a legjobb teljesítmény-memória felhasználási arány elérését célozzák egy adott környezet vagy követelmény esetén.<br/>            A Binary Large Object (BLOB) egy bináris adat, amely egyetlen entitásként tárolódik – azaz a BLOB lehet<br/>            hang, videó vagy magát a bemutató. |
| [`document_level_font_sources`](/slides/python-net/hu/aspose.slides/loadoptions/document_level_font_sources/) | Megadja a külső betűtípusok forrásait, amelyeket a bemutató használni fog.<br/>            Ezek a betűtípusok a bemutató teljes élettartama alatt elérhetők, és nem osztoznak más bemutatókon |
| [`interruption_token`](/slides/python-net/hu/aspose.slides/loadoptions/interruption_token/) | A token az megszakítási kérések figyelésére szolgál.<br/>            <br/>            Ez a token kezeli a teljes [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) példány élettartamát. Bármely hosszú művelet, például a bemutató betöltése<br/>            vagy mentése, a [`InterruptionTokenSource.interrupt`](/slides/python-net/hu/aspose.slides/interruptiontokensource/interrupt) metódus hívásával lesz megszakítva a [`InterruptionTokenSource`](/slides/python-net/hu/aspose.slides/interruptiontokensource)-n. |
| [`resource_loading_callback`](/slides/python-net/hu/aspose.slides/loadoptions/resource_loading_callback/) | Visszaadja vagy beállítja a visszahívási interfészt, amely a külső erőforrások betöltését kezeli.<br/>            Read/write [`IResourceLoadingCallback`](/slides/python-net/hu/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/hu/aspose.slides/loadoptions/spreadsheet_options/) | Lekérdezi a táblázatkezelőkhöz kapcsolódó beállításokat. Például ezek a beállítások befolyásolják a diagramok képleteinek számítását. |
| [`default_text_language`](/slides/python-net/hu/aspose.slides/loadoptions/default_text_language/) | Visszaadja vagy beállítja a bemutató szövegének alapértelmezett nyelvét.<br/>             Read/write **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/hu/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Megmondja, hogy az Aspose.Slides töröl-e minden beágyazott bináris objektumot a bemutató betöltése közben.<br/>            <br/>A beágyazott bináris objektumok típusai:<br/><br/><br/>* VBA Projekt [`IPresentation.vba_project`](/slides/python-net/hu/aspose.slides/ipresentation/vba_project)<br/>* OLE Objektum beágyazott adat [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Vezérlő bináris adat [`IControl.active_x_control_binary`](/slides/python-net/hu/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Read/write **bool**. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)