---
title: IDocumentProperties class
second_title: Aspose.Slides dla Pythona via .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/idocumentproperties/
---
## IDocumentProperties klasa

Reprezentuje właściwości prezentacji.

Typ IDocumentProperties udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`app_version`](/slides/python-net/pl/aspose.slides/idocumentproperties/app_version/) | Zwraca wersję aplikacji.<br/>            Tylko do odczytu **str**. |
| [`name_of_application`](/slides/python-net/pl/aspose.slides/idocumentproperties/name_of_application/) | Zwraca lub ustawia nazwę aplikacji.<br/>            Odczyt/zapis **str**. |
| [`company`](/slides/python-net/pl/aspose.slides/idocumentproperties/company/) | Zwraca lub ustawia właściwość firmy.<br/>            Odczyt/zapis **str**. |
| [`manager`](/slides/python-net/pl/aspose.slides/idocumentproperties/manager/) | Zwraca lub ustawia właściwość menedżera.<br/>            Odczyt/zapis **str**. |
| [`presentation_format`](/slides/python-net/pl/aspose.slides/idocumentproperties/presentation_format/) | Zwraca lub ustawia docelowy format prezentacji.<br/>            Odczyt/zapis **str**. |
| [`shared_doc`](/slides/python-net/pl/aspose.slides/idocumentproperties/shared_doc/) | Określa, czy prezentacja jest współdzielona przez wiele osób.<br/>            Odczyt/zapis **bool**. |
| [`application_template`](/slides/python-net/pl/aspose.slides/idocumentproperties/application_template/) | Zwraca lub ustawia szablon aplikacji.<br/>            Odczyt/zapis **str**. |
| [`total_editing_time`](/slides/python-net/pl/aspose.slides/idocumentproperties/total_editing_time/) | Całkowity czas edycji prezentacji.<br/>            Odczyt/zapis **System.TimeSpan**. |
| [`title`](/slides/python-net/pl/aspose.slides/idocumentproperties/title/) | Zwraca lub ustawia tytuł prezentacji.<br/>            Odczyt/zapis **str**. |
| [`subject`](/slides/python-net/pl/aspose.slides/idocumentproperties/subject/) | Zwraca lub ustawia temat prezentacji.<br/>            Odczyt/zapis **str**. |
| [`author`](/slides/python-net/pl/aspose.slides/idocumentproperties/author/) | Zwraca lub ustawia autora prezentacji.<br/>            Odczyt/zapis **str**. |
| [`keywords`](/slides/python-net/pl/aspose.slides/idocumentproperties/keywords/) | Zwraca lub ustawia słowa kluczowe prezentacji.<br/>            Odczyt/zapis **str**. |
| [`comments`](/slides/python-net/pl/aspose.slides/idocumentproperties/comments/) | Zwraca lub ustawia komentarze prezentacji.<br/>            Odczyt/zapis **str**. |
| [`category`](/slides/python-net/pl/aspose.slides/idocumentproperties/category/) | Zwraca lub ustawia kategorię prezentacji.<br/>            Odczyt/zapis **str**. |
| [`created_time`](/slides/python-net/pl/aspose.slides/idocumentproperties/created_time/) | Zwraca datę utworzenia prezentacji.<br/>            Wartości w UTC.<br/>            Odczyt/zapis **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/pl/aspose.slides/idocumentproperties/last_saved_time/) | Zwraca datę ostatniej modyfikacji prezentacji.<br/>            Wartości w UTC.<br/>            Tylko do odczytu w przypadku Presentation.DocumentProperties (ponieważ będzie aktualizowane wewnętrznie podczas procesu zapisywania obiektu IPresentation). <br/>            Może być zmieniona poprzez instancję DocumentProperties zwracaną przez metodę [`IPresentationInfo.read_document_properties`](/slides/python-net/pl/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Proszę zobaczyć przykład w podsumowaniu metody **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**. |
| [`last_printed`](/slides/python-net/pl/aspose.slides/idocumentproperties/last_printed/) | Zwraca datę ostatniego wydrukowania prezentacji.<br/>            Odczyt/zapis **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/pl/aspose.slides/idocumentproperties/last_saved_by/) | Zwraca lub ustawia nazwę ostatniej osoby, która zmodyfikowała prezentację.<br/>            Odczyt/zapis **str**. |
| [`revision_number`](/slides/python-net/pl/aspose.slides/idocumentproperties/revision_number/) | Zwraca lub ustawia numer rewizji prezentacji.<br/>            Odczyt/zapis **int**. |
| [`content_status`](/slides/python-net/pl/aspose.slides/idocumentproperties/content_status/) | Zwraca lub ustawia status treści prezentacji.<br/>            Odczyt/zapis **str**. |
| [`content_type`](/slides/python-net/pl/aspose.slides/idocumentproperties/content_type/) | Zwraca lub ustawia typ treści prezentacji.<br/>            Odczyt/zapis **str**. |
| [`hyperlink_base`](/slides/python-net/pl/aspose.slides/idocumentproperties/hyperlink_base/) | Zwraca lub ustawia właściwość dokumentu HyperlinkBase.<br/>            Odczyt/zapis **str**. |
| [`scale_crop`](/slides/python-net/pl/aspose.slides/idocumentproperties/scale_crop/) | Wskazuje tryb wyświetlania miniaturki dokumentu.<br/>            Ustaw ten element na **true**, aby włączyć skalowanie miniaturki dokumentu do wyświetlacza.<br/>            Ustaw ten element na **false**, aby włączyć przycinanie miniaturki dokumentu, aby pokazać tylko sekcje pasujące do wyświetlacza.<br/>            Odczyt/zapis **bool**. |
| [`links_up_to_date`](/slides/python-net/pl/aspose.slides/idocumentproperties/links_up_to_date/) | Wskazuje, czy hiperłącza w dokumencie są aktualne.<br/>            Ustaw ten element na **true**, aby zaznaczyć, że hiperłącza są zaktualizowane.<br/>            Ustaw ten element na **false**, aby zaznaczyć, że hiperłącza są nieaktualne.<br/>            Odczyt/zapis **bool**. |
| [`hyperlinks_changed`](/slides/python-net/pl/aspose.slides/idocumentproperties/hyperlinks_changed/) | Określa, że jedno lub więcej hiperłączy w tej części zostało zaktualizowanych wyłącznie w tej części przez producenta.<br/>            Następny producent otwierający ten dokument powinien zaktualizować relacje hiperłączy nowymi hiperłączami określonymi w tej części.<br/>            Odczyt/zapis **bool**. |
| [`slides`](/slides/python-net/pl/aspose.slides/idocumentproperties/slides/) | Określa całkowitą liczbę slajdów w dokumencie prezentacji.<br/pl/>            Tylko do odczytu **int**. |
| [`hidden_slides`](/slides/python-net/pl/aspose.slides/idocumentproperties/hidden_slides/) | Określa liczbę ukrytych slajdów w dokumencie prezentacji.<br/>            Tylko do odczytu **int**. |
| [`notes`](/slides/python-net/pl/aspose.slides/idocumentproperties/notes/) | Określa liczbę slajdów w prezentacji zawierających notatki.<br/>            Tylko do odczytu **int**. |
| [`paragraphs`](/slides/python-net/pl/aspose.slides/idocumentproperties/paragraphs/) | Określa całkowitą liczbę akapitów znalezionych w dokumencie, jeśli dotyczy.<br/>            Tylko do odczytu **int**. |
| [`words`](/slides/python-net/pl/aspose.slides/idocumentproperties/words/) | Określa całkowitą liczbę słów w dokumencie.<br/>            Tylko do odczytu **int**. |
| [`multimedia_clips`](/slides/python-net/pl/aspose.slides/idocumentproperties/multimedia_clips/) | Określa całkowitą liczbę klipów dźwiękowych lub wideo obecnych w dokumencie.<br/>            Tylko do odczytu **int**. |
| [`titles_of_parts`](/slides/python-net/pl/aspose.slides/idocumentproperties/titles_of_parts/) | Określa tytuł każdej części dokumentu.<br/>            Te części nie są fizycznymi częściami dokumentu, lecz konceptualnymi reprezentacjami sekcji dokumentu.<br/>            Tylko do odczytu **List[str]**. |
| [`heading_pairs`](/slides/python-net/pl/aspose.slides/idocumentproperties/heading_pairs/) | Wskazuje grupowanie części dokumentu i liczbę części w każdej grupie.<br/>            Tylko do odczytu **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/pl/aspose.slides/idocumentproperties/count_of_custom_properties/) | Zwraca liczbę własnych właściwości rzeczywiście zawartych w kolekcji.<br/>            Tylko do odczytu **int**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Pobiera nazwany wartość logiczną z własnych właściwości. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Pobiera nazwany wartość całkowitą z własnych właściwości. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Pobiera nazwany wartość DateTime z własnych właściwości. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Pobiera nazwany wartość ciągu znaków z własnych właściwości. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Ustawia nazwany własny parametr logiczny. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Ustawia nazwany własny parametr całkowity. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Ustawia nazwany własny parametr DateTime. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Ustawia nazwany własny parametr ciągu znaków. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Ustawia nazwany własny parametr float. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/pl/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Ustawia nazwany własny parametr double. |
| [`get_custom_property_name(self, index)`](/slides/python-net/pl/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Zwraca nazwę własnej właściwości pod określonym indeksem. |
| [`remove_custom_property(self, name)`](/slides/python-net/pl/aspose.slides/idocumentproperties/remove_custom_property/#str) | Usuwa własną właściwość powiązaną z określoną nazwą. |
| [`contains_custom_property(self, name)`](/slides/python-net/pl/aspose.slides/idocumentproperties/contains_custom_property/#str) | Sprawdza obecność własnej właściwości o określonej nazwie. |
| [`clear_custom_properties(self)`](/slides/python-net/pl/aspose.slides/idocumentproperties/clear_custom_properties/#) | Usuwa wszystkie własne właściwości. |
| [`clear_built_in_properties(self)`](/slides/python-net/pl/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Czyści i ustawia wartości domyślne dla wszystkich wbudowanych właściwości. |
| [`get_sensitivity_labels(self)`](/slides/python-net/pl/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Pobiera tablicę etykiet wrażliwości z własnych właściwości dokumentu (Metadane Microsoft Information Protection SDK). |

### Zobacz również
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)