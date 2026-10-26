---
title: IDocumentProperties class
second_title: Aspose.Slides pro Python přes .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/idocumentproperties/
---
## IDocumentProperties třída

Represents properties of a presentation.

The IDocumentProperties type exposes the following members:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/cs/aspose.slides/idocumentproperties/app_version/) | Vrací verzi aplikace.<br/>            Pouze pro čtení **str**. |
| [`name_of_application`](/slides/python-net/cs/aspose.slides/idocumentproperties/name_of_application/) | Vrací nebo nastavuje název aplikace.<br/>            Čtení a zápis **str**. |
| [`company`](/slides/python-net/cs/aspose.slides/idocumentproperties/company/) | Vrací nebo nastavuje vlastnost společnosti.<br/>            Čtení a zápis **str**. |
| [`manager`](/slides/python-net/cs/aspose.slides/idocumentproperties/manager/) | Vrací nebo nastavuje vlastnost manažera.<br/>            Čtení a zápis **str**. |
| [`presentation_format`](/slides/python-net/cs/aspose.slides/idocumentproperties/presentation_format/) | Vrací nebo nastavuje zamýšlený formát prezentace.<br/>            Čtení a zápis **str**. |
| [`shared_doc`](/slides/python-net/cs/aspose.slides/idocumentproperties/shared_doc/) | Určuje, zda je prezentace sdílena mezi více lidmi.<br/>            Čtení a zápis **bool**. |
| [`application_template`](/slides/python-net/cs/aspose.slides/idocumentproperties/application_template/) | Vrací nebo nastavuje šablonu aplikace.<br/>            Čtení a zápis **str**. |
| [`total_editing_time`](/slides/python-net/cs/aspose.slides/idocumentproperties/total_editing_time/) | Celková doba úprav prezentace.<br/>            Čtení a zápis **System.TimeSpan**. |
| [`title`](/slides/python-net/cs/aspose.slides/idocumentproperties/title/) | Vrací nebo nastavuje název prezentace.<br/>            Čtení a zápis **str**. |
| [`subject`](/slides/python-net/cs/aspose.slides/idocumentproperties/subject/) | Vrací nebo nastavuje předmět prezentace.<br/>            Čtení a zápis **str**. |
| [`author`](/slides/python-net/cs/aspose.slides/idocumentproperties/author/) | Vrací nebo nastavuje autora prezentace.<br/>            Čtení a zápis **str**. |
| [`keywords`](/slides/python-net/cs/aspose.slides/idocumentproperties/keywords/) | Vrací nebo nastavuje klíčová slova prezentace.<br/>            Čtení a zápis **str**. |
| [`comments`](/slides/python-net/cs/aspose.slides/idocumentproperties/comments/) | Vrací nebo nastavuje komentáře k prezentaci.<br/>            Čtení a zápis **str**. |
| [`category`](/slides/python-net/cs/aspose.slides/idocumentproperties/category/) | Vrací nebo nastavuje kategorii prezentace.<br/>            Čtení a zápis **str**. |
| [`created_time`](/slides/python-net/cs/aspose.slides/idocumentproperties/created_time/) | Vrací datum vytvoření prezentace.<br/>            Hodnoty jsou v UTC.<br/>            Čtení a zápis **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/cs/aspose.slides/idocumentproperties/last_saved_time/) | Vrací datum poslední úpravy prezentace.<br/>            Hodnoty jsou v UTC.<br/>            Pouze pro čtení v případě Presentation.DocumentProperties (protože bude interně aktualizováno během procesu ukládání objektu IPresentation). <br/>            Lze změnit pomocí instance DocumentProperties vrácené metodou [`IPresentationInfo.read_document_properties`](/slides/python-net/cs/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Podívejte se na příklad v souhrnu metody **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**. |
| [`last_printed`](/slides/python-net/cs/aspose.slides/idocumentproperties/last_printed/) | Vrací datum posledního tisku prezentace.<br/>            Čtení a zápis **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/cs/aspose.slides/idocumentproperties/last_saved_by/) | Vrací nebo nastavuje jméno poslední osoby, která prezentaci upravila.<br/>            Čtení a zápis **str**. |
| [`revision_number`](/slides/python-net/cs/aspose.slides/idocumentproperties/revision_number/) | Vrací nebo nastavuje číslo revize prezentace.<br/>            Čtení a zápis **int**. |
| [`content_status`](/slides/python-net/cs/aspose.slides/idocumentproperties/content_status/) | Vrací nebo nastavuje stav obsahu prezentace.<br/>            Čtení a zápis **str**. |
| [`content_type`](/slides/python-net/cs/aspose.slides/idocumentproperties/content_type/) | Vrací nebo nastavuje typ obsahu prezentace.<br/>            Čtení a zápis **str**. |
| [`hyperlink_base`](/slides/python-net/cs/aspose.slides/idocumentproperties/hyperlink_base/) | Vrací nebo nastavuje vlastnost dokumentu HyperlinkBase.<br/>            Čtení a zápis **str**. |
| [`scale_crop`](/slides/python-net/cs/aspose.slides/idocumentproperties/scale_crop/) | Udává režim zobrazení náhledu dokumentu.<br/>            Nastavte tento prvek na **true**, aby se povolilo škálování náhledu dokumentu na obrazovku.<br/>            Nastavte tento prvek na **false**, aby se povolilo oříznutí náhledu dokumentu tak, aby se zobrazily pouze části, které se vejdou na obrazovku.<br/>            Čtení a zápis **bool**. |
| [`links_up_to_date`](/slides/python-net/cs/aspose.slides/idocumentproperties/links_up_to_date/) | Udává, zda jsou hypertextové odkazy v dokumentu aktuální.<br/>            Nastavte tento prvek na **true**, aby se označilo, že odkazy jsou aktualizovány.<br/>            Nastavte tento prvek na **false**, aby se označilo, že odkazy jsou zastaralé.<br/>            Čtení a zápis **bool**. |
| [`hyperlinks_changed`](/slides/python-net/cs/aspose.slides/idocumentproperties/hyperlinks_changed/) | Specifikuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části producentem.<br/>            Další producent, který otevře tento dokument, by měl aktualizovat vztahy hypertextových odkazů pomocí nových odkazů uvedených v této části.<br/>            Čtení a zápis **bool**. |
| [`slides`](/slides/python-net/cs/aspose.slides/idocumentproperties/slides/) | Určuje celkový počet snímků v dokumentu prezentace.<br/cs/>            Pouze pro čtení **int**. |
| [`hidden_slides`](/slides/python-net/cs/aspose.slides/idocumentproperties/hidden_slides/) | Určuje počet skrytých snímků v dokumentu prezentace.<br/>            Pouze pro čtení **int**. |
| [`notes`](/slides/python-net/cs/aspose.slides/idocumentproperties/notes/) | Určuje počet snímků v prezentaci obsahujících poznámky.<br/>            Pouze pro čtení **int**. |
| [`paragraphs`](/slides/python-net/cs/aspose.slides/idocumentproperties/paragraphs/) | Určuje celkový počet odstavců v dokumentu, pokud jsou k dispozici.<br/>            Pouze pro čtení **int**. |
| [`words`](/slides/python-net/cs/aspose.slides/idocumentproperties/words/) | Určuje celkový počet slov v dokumentu.<br/>            Pouze pro čtení **int**. |
| [`multimedia_clips`](/slides/python-net/cs/aspose.slides/idocumentproperties/multimedia_clips/) | Určuje celkový počet zvukových nebo video klipů v dokumentu.<br/>            Pouze pro čtení **int**. |
| [`titles_of_parts`](/slides/python-net/cs/aspose.slides/idocumentproperties/titles_of_parts/) | Určuje název každé části dokumentu.<br/>            Tyto části nejsou skutečnými částmi dokumentu, ale koncepčními reprezentacemi sekcí dokumentu.<br/>            Pouze pro čtení **List[str]**. |
| [`heading_pairs`](/slides/python-net/cs/aspose.slides/idocumentproperties/heading_pairs/) | Udává seskupení částí dokumentu a počet částí v každé skupině.<br/>            Pouze pro čtení **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/cs/aspose.slides/idocumentproperties/count_of_custom_properties/) | Vrací počet vlastních vlastností skutečně obsažených ve sbírce.<br/>            Pouze pro čtení **int**. |

## Metody

| Method | Description |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Získá pojmenovanou boolean hodnotu z vlastních vlastností. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Získá pojmenovanou celočíselnou hodnotu z vlastních vlastností. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Získá pojmenovanou hodnotu DateTime z vlastních vlastností. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Získá pojmenovanou řetězcovou hodnotu z vlastních vlastností. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Nastaví pojmenovanou boolean vlastnost. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Nastaví pojmenovanou celočíselnou vlastnost. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Nastaví pojmenovanou DateTime vlastnost. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Nastaví pojmenovanou řetězcovou vlastnost. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Nastaví pojmenovanou float vlastnost. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/cs/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Nastaví pojmenovanou double vlastnost. |
| [`get_custom_property_name(self, index)`](/slides/python-net/cs/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Vrátí název vlastní vlastnosti na zadaném indexu. |
| [`remove_custom_property(self, name)`](/slides/python-net/cs/aspose.slides/idocumentproperties/remove_custom_property/#str) | Odstraní vlastní vlastnost spojenou se zadaným názvem. |
| [`contains_custom_property(self, name)`](/slides/python-net/cs/aspose.slides/idocumentproperties/contains_custom_property/#str) | Zkontroluje přítomnost vlastní vlastnosti se zadaným názvem. |
| [`clear_custom_properties(self)`](/slides/python-net/cs/aspose.slides/idocumentproperties/clear_custom_properties/#) | Odstraní všechny vlastní vlastnosti. |
| [`clear_built_in_properties(self)`](/slides/python-net/cs/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Vyčistí a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti. |
| [`get_sensitivity_labels(self)`](/slides/python-net/cs/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Získá pole citlivostních štítků z vlastních vlastností dokumentu (Metadata Microsoft Information Protection SDK). |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)