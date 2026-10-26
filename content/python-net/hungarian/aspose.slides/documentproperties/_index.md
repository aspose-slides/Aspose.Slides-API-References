---
title: DocumentProperties class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/documentproperties/
---
## DocumentProperties osztály

A prezentáció tulajdonságait képviseli.

A DocumentProperties típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/documentproperties/__init__/#) | Új példányt inicializál a(z) [`DocumentProperties`](/slides/python-net/hu/aspose.slides/documentproperties) osztályból. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`app_version`](/slides/python-net/hu/aspose.slides/documentproperties/app_version/) | Visszaadja az alkalmazás verzióját.<br/>            Csak olvasható **str**. |
| [`name_of_application`](/slides/python-net/hu/aspose.slides/documentproperties/name_of_application/) | Visszaadja vagy beállítja az alkalmazás nevét.<br/>            Olvasás/írás **str**. |
| [`company`](/slides/python-net/hu/aspose.slides/documentproperties/company/) | Visszaadja vagy beállítja a cég tulajdonságát.<br/>            Olvasás/írás **str**. |
| [`manager`](/slides/python-net/hu/aspose.slides/documentproperties/manager/) | Visszaadja vagy beállítja a vezető tulajdonságát.<br/>            Olvasás/írás **str**. |
| [`presentation_format`](/slides/python-net/hu/aspose.slides/documentproperties/presentation_format/) | Visszaadja vagy beállítja a prezentáció kívánt formátumát.<br/>            Olvasás/írás **str**. |
| [`shared_doc`](/slides/python-net/hu/aspose.slides/documentproperties/shared_doc/) | Megállapítja, hogy a prezentáció több személy között meg van-e osztva.<br/>            Olvasás/írás **bool**. |
| [`application_template`](/slides/python-net/hu/aspose.slides/documentproperties/application_template/) | Visszaadja vagy beállítja egy alkalmazás sablonját.<br/>            Olvasás/írás **str**. |
| [`total_editing_time`](/slides/python-net/hu/aspose.slides/documentproperties/total_editing_time/) | A prezentáció teljes szerkesztési ideje.<br/>            Olvasás/írás **System.TimeSpan**. |
| [`title`](/slides/python-net/hu/aspose.slides/documentproperties/title/) | Visszaadja vagy beállítja a prezentáció címét.<br/>            Olvasás/írás **str**. |
| [`subject`](/slides/python-net/hu/aspose.slides/documentproperties/subject/) | Visszaadja vagy beállítja a prezentáció tárgyát.<br/>            Olvasás/írás **str**. |
| [`author`](/slides/python-net/hu/aspose.slides/documentproperties/author/) | Visszaadja vagy beállítja a prezentáció szerzőjét.<br/>            Olvasás/írás **str**. |
| [`keywords`](/slides/python-net/hu/aspose.slides/documentproperties/keywords/) | Visszaadja vagy beállítja a prezentáció kulcsszavait.<br/>            Olvasás/írás **str**. |
| [`comments`](/slides/python-net/hu/aspose.slides/documentproperties/comments/) | Visszaadja vagy beállítja a prezentáció megjegyzéseit.<br/>            Olvasás/írás **str**. |
| [`category`](/slides/python-net/hu/aspose.slides/documentproperties/category/) | Visszaadja vagy beállítja a prezentáció kategóriáját.<br/>            Olvasás/írás **str**. |
| [`created_time`](/slides/python-net/hu/aspose.slides/documentproperties/created_time/) | Visszaadja a prezentáció létrehozásának dátumát.<br/>            Az értékek UTC-ben vannak.<br/>            Olvasás/írás **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/hu/aspose.slides/documentproperties/last_saved_time/) | Visszaadja a prezentáció legutóbbi módosításának dátumát.<br/>            Az értékek UTC-ben vannak.<br/>            Csak olvasható a Presentation.DocumentProperties esetén (mivel a mentési folyamat során belsőleg frissül).<br/>            A [`IPresentationInfo.read_document_properties`](/slides/python-net/hu/aspose.slides/ipresentationinfo/read_document_properties) módszer által visszaadott DocumentProperties példányon keresztül módosítható.<br/>            Lásd a példát a **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** metódus összefoglalójában. |
| [`last_printed`](/slides/python-net/hu/aspose.slides/documentproperties/last_printed/) | Visszaadja a prezentáció legutóbbi nyomtatásának dátumát.<br/>            Olvasás/írás **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/hu/aspose.slides/documentproperties/last_saved_by/) | Visszaadja vagy beállítja a prezentációt legutóbb módosító személy nevét.<br/>            Olvasás/írás **str**. |
| [`revision_number`](/slides/python-net/hu/aspose.slides/documentproperties/revision_number/) | Visszaadja vagy beállítja a prezentáció revíziószámát.<br/>            Olvasás/írás **int**. |
| [`content_status`](/slides/python-net/hu/aspose.slides/documentproperties/content_status/) | Visszaadja vagy beállítja a prezentáció tartalomállapotát.<br/>            Olvasás/írás **str**. |
| [`content_type`](/slides/python-net/hu/aspose.slides/documentproperties/content_type/) | Visszaadja vagy beállítja a prezentáció tartalomtípusát.<br/>            Olvasás/írás **str**. |
| [`hyperlink_base`](/slides/python-net/hu/aspose.slides/documentproperties/hyperlink_base/) | Visszaadja vagy beállítja a HyperlinkBase dokumentum tulajdonságot.<br/>            Olvasás/írás **str**. |
| [`count_of_custom_properties`](/slides/python-net/hu/aspose.slides/documentproperties/count_of_custom_properties/) | Visszaadja a gyűjteményben ténylegesen található egyedi tulajdonságok számát.<br/>            Csak olvasható **int**. |
| [`scale_crop`](/slides/python-net/hu/aspose.slides/documentproperties/scale_crop/) | A dokumentum előnézetének megjelenítési módját jelzi.<br/>            Állítsd **true**-ra ezt az elemet a dokumentum előnézet skálázásának engedélyezéséhez a megjelenítőn.<br/>            Állítsd **false**-ra ezt az elemet a dokumentum előnézet vágásának engedélyezéséhez, hogy csak a megjelenítőnek megfelelő szakaszok látszódjanak.<br/>            Olvasás/írás **bool**. |
| [`links_up_to_date`](/slides/python-net/hu/aspose.slides/documentproperties/links_up_to_date/) | A dokumentumban szereplő hiperhivatkozások naprakész állapotát jelzi.<br/>            Állítsd **true**-ra ezt az elemet a hiperhivatkozások frissítettnek jelzéséhez.<br/>            Állítsd **false**-ra ezt az elemet a hiperhivatkozások elavultnak jelzéséhez.<br/>            Olvasás/írás **bool**. |
| [`hyperlinks_changed`](/slides/python-net/hu/aspose.slides/documentproperties/hyperlinks_changed/) | Azt határozza meg, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag egy előállító által lett frissítve.<br/>            A dokumentumot a következő előállító megnyitásakor frissítenie kell a hiperhivatkozási kapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal.<br/>            Olvasás/írás **bool**. |
| [`slides`](/slides/python-net/hu/aspose.slides/documentproperties/slides/) | Visszaadja a prezentációs dokumentumban található diák teljes számát.<br/hu/>            Csak olvasható **int**. |
| [`hidden_slides`](/slides/python-net/hu/aspose.slides/documentproperties/hidden_slides/) | Visszaadja a prezentációs dokumentumban található rejtett diák számát.<br/>            Csak olvasható **int**. |
| [`notes`](/slides/python-net/hu/aspose.slides/documentproperties/notes/) | Visszaadja a prezentációban megjegyzésekkel rendelkező diák számát.<br/>            Csak olvasható **int**. |
| [`paragraphs`](/slides/python-net/hu/aspose.slides/documentproperties/paragraphs/) | Visszaadja a dokumentumban megtalálható bekezdések teljes számát, ha alkalmazható.<br/>            Csak olvasható **int**. |
| [`words`](/slides/python-net/hu/aspose.slides/documentproperties/words/) | Visszaadja a dokumentumban található szavak teljes számát.<br/>            Csak olvasható **int**. |
| [`multimedia_clips`](/slides/python-net/hu/aspose.slides/documentproperties/multimedia_clips/) | Visszaadja a dokumentumban jelen lévő hang- vagy videoklipek teljes számát.<br/>            Csak olvasható **int**. |
| [`titles_of_parts`](/slides/python-net/hu/aspose.slides/documentproperties/titles_of_parts/) | Megadja minden dokumentumrész címét.<br/>            Ezek a részek nem dokumentumrészek, hanem a dokumentum szakaszainak koncepciós ábrázolásai.<br/>            Csak olvasható **List[str]**. |
| [`heading_pairs`](/slides/python-net/hu/aspose.slides/documentproperties/heading_pairs/) | Jelzi a dokumentumrészek csoportosítását és az egyes csoportokban lévő részek számát.<br/>            Csak olvasható **List[IHeadingPair]**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Lekéri a név szerint meghatározott logikai értéket az egyedi tulajdonságokból. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Lekéri a név szerint meghatározott egész értéket az egyedi tulajdonságokból. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Lekéri a név szerint meghatározott DateTime értéket az egyedi tulajdonságokból. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Lekéri a név szerint meghatározott karakterlánc értéket az egyedi tulajdonságokból. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | Beállít egy név szerint meghatározott logikai egyedi tulajdonságot. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/set_custom_property_value/#str-int) | Beállít egy név szerint meghatározott egész egyedi tulajdonságot. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | Beállít egy név szerint meghatározott DateTime egyedi tulajdonságot. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/set_custom_property_value/#str-str) | Beállít egy név szerint meghatározott karakterlánc egyedi tulajdonságot. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Beállít egy név szerint meghatározott float egyedi tulajdonságot. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Beállít egy név szerint meghatározott double egyedi tulajdonságot. |
| [`get_custom_property_name(self, index)`](/slides/python-net/hu/aspose.slides/documentproperties/get_custom_property_name/#int) | Visszaad egy egyedi tulajdonság nevét a megadott indexen. |
| [`remove_custom_property(self, name)`](/slides/python-net/hu/aspose.slides/documentproperties/remove_custom_property/#str) | Eltávolít egy megadott névhez kapcsolódó egyedi tulajdonságot. |
| [`contains_custom_property(self, name)`](/slides/python-net/hu/aspose.slides/documentproperties/contains_custom_property/#str) | Ellenőrzi egy megadott névű egyedi tulajdonság jelenlétét. |
| [`clear_custom_properties(self)`](/slides/python-net/hu/aspose.slides/documentproperties/clear_custom_properties/#) | Eltávolít minden egyedi tulajdonságot. |
| [`get_sensitivity_labels(self)`](/slides/python-net/hu/aspose.slides/documentproperties/get_sensitivity_labels/#) | Lekéri a szenzitivitási címkék tömbjét az egyedi dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata). |
| [`clear_built_in_properties(self)`](/slides/python-net/hu/aspose.slides/documentproperties/clear_built_in_properties/#) | Törli és beállítja az alapértelmezett értékeket az összes beépített tulajdonságra. |
| [`clone(self)`](/slides/python-net/hu/aspose.slides/documentproperties/clone/#) | Klónozza a jelenlegi objektumot |
| [`clone_t(self)`](/slides/python-net/hu/aspose.slides/documentproperties/clone_t/#) | Klónozza a jelenlegi objektumot |

### Lásd még
* osztály [`DocumentProperties`](/slides/python-net/hu/aspose.slides/documentproperties)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)