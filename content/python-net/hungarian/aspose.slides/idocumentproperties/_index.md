---
title: IDocumentProperties class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referenciakönyv
description: 
type: docs
url: /hu/aspose.slides/idocumentproperties/
---
## IDocumentProperties osztály

A prezentáció tulajdonságait reprezentálja.

Az IDocumentProperties típus a következő tagokat teszi közzé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/hu/aspose.slides/idocumentproperties/app_version/) | Visszaadja az alkalmazás verzióját.<br/>            Csak olvasható **str**. |
| [`name_of_application`](/slides/python-net/hu/aspose.slides/idocumentproperties/name_of_application/) | Visszaadja vagy beállítja az alkalmazás nevét.<br/>            Olvasás/írás **str**. |
| [`company`](/slides/python-net/hu/aspose.slides/idocumentproperties/company/) | Visszaadja vagy beállítja a cég tulajdonságát.<br/>            Olvasás/írás **str**. |
| [`manager`](/slides/python-net/hu/aspose.slides/idocumentproperties/manager/) | Visszaadja vagy beállítja a menedzser tulajdonságát.<br/>            Olvasás/írás **str**. |
| [`presentation_format`](/slides/python-net/hu/aspose.slides/idocumentproperties/presentation_format/) | Visszaadja vagy beállítja a prezentáció kívánt formátumát.<br/>            Olvasás/írás **str**. |
| [`shared_doc`](/slides/python-net/hu/aspose.slides/idocumentproperties/shared_doc/) | Megállapítja, hogy a prezentáció több személy között van-e megosztva.<br/>            Olvasás/írás **bool**. |
| [`application_template`](/slides/python-net/hu/aspose.slides/idocumentproperties/application_template/) | Visszaadja vagy beállítja az alkalmazás sablonját.<br/>            Olvasás/írás **str**. |
| [`total_editing_time`](/slides/python-net/hu/aspose.slides/idocumentproperties/total_editing_time/) | A prezentáció összes szerkesztési ideje.<br/>            Olvasás/írás **System.TimeSpan**. |
| [`title`](/slides/python-net/hu/aspose.slides/idocumentproperties/title/) | Visszaadja vagy beállítja a prezentáció címét.<br/>            Olvasás/írás **str**. |
| [`subject`](/slides/python-net/hu/aspose.slides/idocumentproperties/subject/) | Visszaadja vagy beállítja a prezentáció tárgyát.<br/>            Olvasás/írás **str**. |
| [`author`](/slides/python-net/hu/aspose.slides/idocumentproperties/author/) | Visszaadja vagy beállítja a prezentáció szerzőjét.<br/>            Olvasás/írás **str**. |
| [`keywords`](/slides/python-net/hu/aspose.slides/idocumentproperties/keywords/) | Visszaadja vagy beállítja a prezentáció kulcsszavait.<br/>            Olvasás/írás **str**. |
| [`comments`](/slides/python-net/hu/aspose.slides/idocumentproperties/comments/) | Visszaadja vagy beállítja a prezentáció megjegyzéseit.<br/>            Olvasás/írás **str**. |
| [`category`](/slides/python-net/hu/aspose.slides/idocumentproperties/category/) | Visszaadja vagy beállítja a prezentáció kategóriáját.<br/>            Olvasás/írás **str**. |
| [`created_time`](/slides/python-net/hu/aspose.slides/idocumentproperties/created_time/) | Visszaadja a prezentáció létrehozásának dátumát. <br/>            Az értékek UTC-ben vannak.<br/>            Olvasás/írás **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/hu/aspose.slides/idocumentproperties/last_saved_time/) | Visszaadja a prezentáció utolsó módosításának dátumát.<br/>            Az értékek UTC-ben vannak.<br/>            Csak olvasható a Presentation.DocumentProperties esetén (mert a mentési folyamat során az IPresentation objektum belül frissül).<br/>            Módosítható a [`IPresentationInfo.read_document_properties`](/slides/python-net/hu/aspose.slides/ipresentationinfo/read_document_properties) metódus által visszaadott DocumentProperties példányon keresztül.<br/>            Tekintse meg a példát a **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** metódus összefoglalójában. |
| [`last_printed`](/slides/python-net/hu/aspose.slides/idocumentproperties/last_printed/) | Visszaadja a prezentáció legutóbbi nyomtatásának dátumát.<br/>            Olvasás/írás **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/hu/aspose.slides/idocumentproperties/last_saved_by/) | Visszaadja vagy beállítja a prezentációt utoljára módosító személy nevét.<br/>            Olvasás/írás **str**. |
| [`revision_number`](/slides/python-net/hu/aspose.slides/idocumentproperties/revision_number/) | Visszaadja vagy beállítja a prezentáció revíziószámát.<br/>            Olvasás/írás **int**. |
| [`content_status`](/slides/python-net/hu/aspose.slides/idocumentproperties/content_status/) | Visszaadja vagy beállítja a prezentáció tartalom állapotát.<br/>            Olvasás/írás **str**. |
| [`content_type`](/slides/python-net/hu/aspose.slides/idocumentproperties/content_type/) | Visszaadja vagy beállítja a prezentáció tartalomtípusát.<br/>            Olvasás/írás **str**. |
| [`hyperlink_base`](/slides/python-net/hu/aspose.slides/idocumentproperties/hyperlink_base/) | Visszaadja vagy beállítja a HyperlinkBase dokumentumtulajdonságot.<br/>            Olvasás/írás **str**. |
| [`scale_crop`](/slides/python-net/hu/aspose.slides/idocumentproperties/scale_crop/) | Jelzi a dokumentum miniatűr megjelenítési módját.<br/>            Állítsa ezt az elemet **true**-ra a miniatűr méretezésének engedélyezéséhez a kijelzőn.<br/>            Állítsa ezt az elemet **false**-ra a miniatűr vágásának engedélyezéséhez, hogy csak a kijelzőnek megfelelő részeket mutassa.<br/>            Olvasás/írás **bool**. |
| [`links_up_to_date`](/slides/python-net/hu/aspose.slides/idocumentproperties/links_up_to_date/) | Jelzi, hogy a dokumentum hiperhivatkozásai naprakészek-e.<br/>            Állítsa ezt az elemet **true**-ra, ha a hiperhivatkozások frissítve vannak.<br/>            Állítsa ezt az elemet **false**-ra, ha a hiperhivatkozások elavultak.<br/>            Olvasás/írás **bool**. |
| [`hyperlinks_changed`](/slides/python-net/hu/aspose.slides/idocumentproperties/hyperlinks_changed/) | Azt határozza meg, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag egy gyártó által került frissítésre.<br/>            A következő gyártó, aki megnyitja a dokumentumot, frissíti a hiperhivatkozási kapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal.<br/>            Olvasás/írás **bool**. |
| [`slides`](/slides/python-net/hu/aspose.slides/idocumentproperties/slides/) | Meghatározza a prezentáció dokumentumban található diák összes számát.<br/hu/>            Csak olvasható **int**. |
| [`hidden_slides`](/slides/python-net/hu/aspose.slides/idocumentproperties/hidden_slides/) | Meghatározza a prezentáció dokumentumban található rejtett diák számát.<br/>            Csak olvasható **int**. |
| [`notes`](/slides/python-net/hu/aspose.slides/idocumentproperties/notes/) | Meghatározza a jegyzeteket tartalmazó diák számát a prezentációban.<br/>            Csak olvasható **int**. |
| [`paragraphs`](/slides/python-net/hu/aspose.slides/idocumentproperties/paragraphs/) | Meghatározza a dokumentumban (ha alkalmazható) megtalált bekezdések összes számát.<br/>            Csak olvasható **int**. |
| [`words`](/slides/python-net/hu/aspose.slides/idocumentproperties/words/) | Meghatározza a dokumentumban található szavak összes számát.<br/>            Csak olvasható **int**. |
| [`multimedia_clips`](/slides/python-net/hu/aspose.slides/idocumentproperties/multimedia_clips/) | Meghatározza a dokumentumban jelen lévő hang- vagy videoklipek összes számát.<br/>            Csak olvasható **int**. |
| [`titles_of_parts`](/slides/python-net/hu/aspose.slides/idocumentproperties/titles_of_parts/) | Meghatározza minden dokumentumrész címét.<br/>            Ezek a részek nem dokumentumrészek, hanem a dokumentumszakaszok koncepcionális ábrázolásai.<br/>            Csak olvasható **List[str]**. |
| [`heading_pairs`](/slides/python-net/hu/aspose.slides/idocumentproperties/heading_pairs/) | Jelzi a dokumentumrészek csoportosítását és az egyes csoportokban lévő részek számát.<br/>            Csak olvasható **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/hu/aspose.slides/idocumentproperties/count_of_custom_properties/) | Visszaadja a gyűjteményben ténylegesen található egyedi tulajdonságok számát.<br/>            Csak olvasható **int**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Lekéri egy nevű logikai értéket az egyedi tulajdonságokból. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Lekéri egy nevű egész értéket az egyedi tulajdonságokból. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Lekéri egy nevű DateTime értéket az egyedi tulajdonságokból. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Lekéri egy nevű karakterlánc értéket az egyedi tulajdonságokból. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Beállít egy nevű logikai egyedi tulajdonságot. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Beállít egy nevű egész egyedi tulajdonságot. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Beállít egy nevű DateTime egyedi tulajdonságot. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Beállít egy nevű karakterlánc egyedi tulajdonságot. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Beállít egy nevű float egyedi tulajdonságot. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/hu/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Beállít egy nevű double egyedi tulajdonságot. |
| [`get_custom_property_name(self, index)`](/slides/python-net/hu/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Visszaad egy egyedi tulajdonság nevet a megadott indexen. |
| [`remove_custom_property(self, name)`](/slides/python-net/hu/aspose.slides/idocumentproperties/remove_custom_property/#str) | Eltávolít egy megadott névhez kapcsolódó egyedi tulajdonságot. |
| [`contains_custom_property(self, name)`](/slides/python-net/hu/aspose.slides/idocumentproperties/contains_custom_property/#str) | Ellenőrzi egy megadott névű egyedi tulajdonság jelenlétét. |
| [`clear_custom_properties(self)`](/slides/python-net/hu/aspose.slides/idocumentproperties/clear_custom_properties/#) | Eltávolítja az összes egyedi tulajdonságot. |
| [`clear_built_in_properties(self)`](/slides/python-net/hu/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Törli és alapértelmezett értékeket állít be az összes beépített tulajdonságra. |
| [`get_sensitivity_labels(self)`](/slides/python-net/hu/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Lekéri a citkossági címkéket az egyedi dokumentumtulajdonságokból (Microsoft Information Protection SDK metaadatok). |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)