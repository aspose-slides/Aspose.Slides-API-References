---
title: DocumentProperties class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/documentproperties/
---
## DocumentProperties klass

Representerar egenskaper för en presentation.

DocumentProperties-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/documentproperties/__init__/#) | Initialiserar en ny instans av klassen [`DocumentProperties`](/slides/python-net/sv/aspose.slides/documentproperties). |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`app_version`](/slides/python-net/sv/aspose.slides/documentproperties/app_version/) | Returnerar appens version.<br/>            Skrivskyddad **str**. |
| [`name_of_application`](/slides/python-net/sv/aspose.slides/documentproperties/name_of_application/) | Returnerar eller anger applikationens namn.<br/>            Läs/skriv **str**. |
| [`company`](/slides/python-net/sv/aspose.slides/documentproperties/company/) | Returnerar eller anger företagsegenskapen.<br/>            Läs/skriv **str**. |
| [`manager`](/slides/python-net/sv/aspose.slides/documentproperties/manager/) | Returnerar eller anger chefsegenskapen.<br/>            Läs/skriv **str**. |
| [`presentation_format`](/slides/python-net/sv/aspose.slides/documentproperties/presentation_format/) | Returnerar eller anger önskat format för en presentation.<br/>            Läs/skriv **str**. |
| [`shared_doc`](/slides/python-net/sv/aspose.slides/documentproperties/shared_doc/) | Fastställer om presentationen delas mellan flera personer.<br/>            Läs/skriv **bool**. |
| [`application_template`](/slides/python-net/sv/aspose.slides/documentproperties/application_template/) | Returnerar eller anger mallen för en applikation.<br/>            Läs/skriv **str**. |
| [`total_editing_time`](/slides/python-net/sv/aspose.slides/documentproperties/total_editing_time/) | Total redigeringstid för en presentation.<br/>            Läs/skriv **System.TimeSpan**. |
| [`title`](/slides/python-net/sv/aspose.slides/documentproperties/title/) | Returnerar eller anger titeln på en presentation.<br/>            Läs/skriv **str**. |
| [`subject`](/slides/python-net/sv/aspose.slides/documentproperties/subject/) | Returnerar eller anger ämnet för en presentation.<br/>            Läs/skriv **str**. |
| [`author`](/slides/python-net/sv/aspose.slides/documentproperties/author/) | Returnerar eller anger författaren till en presentation.<br/>            Läs/skriv **str**. |
| [`keywords`](/slides/python-net/sv/aspose.slides/documentproperties/keywords/) | Returnerar eller anger nyckelorden för en presentation.<br/>            Läs/skriv **str**. |
| [`comments`](/slides/python-net/sv/aspose.slides/documentproperties/comments/) | Returnerar eller anger kommentarer för en presentation.<br/>            Läs/skriv **str**. |
| [`category`](/slides/python-net/sv/aspose.slides/documentproperties/category/) | Returnerar eller anger kategorin för en presentation.<br/>            Läs/skriv **str**. |
| [`created_time`](/slides/python-net/sv/aspose.slides/documentproperties/created_time/) | Returnerar datumet då en presentation skapades.<br/>            Värden är i UTC.<br/>            Läs/skriv **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/sv/aspose.slides/documentproperties/last_saved_time/) | Returnerar datumet då en presentation senast modifierades.<br/>            Värden är i UTC.<br/>            Skrivskyddad i fallet Presentation.DocumentProperties (eftersom den kommer att uppdateras internt under IPresentation-objektets sparprocess). <br/>            Kan ändras via DocumentProperties-instansen som returneras av metoden [`IPresentationInfo.read_document_properties`](/slides/python-net/sv/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Se exempel i **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** metodsammanfattning. |
| [`last_printed`](/slides/python-net/sv/aspose.slides/documentproperties/last_printed/) | Returnerar datumet då en presentation senast trycktes.<br/>            Läs/skriv **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/sv/aspose.slides/documentproperties/last_saved_by/) | Returnerar eller anger namnet på den senaste personen som ändrade en presentation.<br/>            Läs/skriv **str**. |
| [`revision_number`](/slides/python-net/sv/aspose.slides/documentproperties/revision_number/) | Returnerar eller anger presentations revisionsnummer.<br/>            Läs/skriv **int**. |
| [`content_status`](/slides/python-net/sv/aspose.slides/documentproperties/content_status/) | Returnerar eller anger innehållsstatus för en presentation.<br/>            Läs/skriv **str**. |
| [`content_type`](/slides/python-net/sv/aspose.slides/documentproperties/content_type/) | Returnerar eller anger innehållstyp för en presentation.<br/>            Läs/skriv **str**. |
| [`hyperlink_base`](/slides/python-net/sv/aspose.slides/documentproperties/hyperlink_base/) | Returnerar eller anger dokumentegenskapen HyperlinkBase.<br/>            Läs/skriv **str**. |
| [`count_of_custom_properties`](/slides/python-net/sv/aspose.slides/documentproperties/count_of_custom_properties/) | Returnerar antalet anpassade egenskaper som faktiskt finns i en samling.<br/>            Skrivskyddad **int**. |
| [`scale_crop`](/slides/python-net/sv/aspose.slides/documentproperties/scale_crop/) | Anger visningsläget för dokumentets miniatyrbild. <br/>            Sätt detta element till **true** för att möjliggöra skalning av miniatyrbilden till displayen. <br/>            Sätt detta element till **false** för att möjliggöra beskärning av miniatyrbilden så att endast sektioner som passar displayen visas.<br/>            Läs/skriv **bool**. |
| [`links_up_to_date`](/slides/python-net/sv/aspose.slides/documentproperties/links_up_to_date/) | Anger om hyperlänkar i ett dokument är aktuella. <br/>            Sätt detta element till **true** för att indikera att hyperlänkar är uppdaterade. <br/>            Sätt detta element till **false** för att indikera att hyperlänkar är föråldrade.<br/>            Läs/skriv **bool**. |
| [`hyperlinks_changed`](/slides/python-net/sv/aspose.slides/documentproperties/hyperlinks_changed/) | Anger att en eller flera hyperlänkar i denna del har uppdaterats exklusivt i denna del av en producent. <br/>            Nästa producent som öppnar detta dokument ska uppdatera hyperlänkrelationerna med de nya hyperlänkar som anges i denna del.<br/>            Läs/skriv **bool**. |
| [`slides`](/slides/python-net/sv/aspose.slides/documentproperties/slides/) | Returnerar det totala antalet bilder i ett presentationsdokument.<br/sv/>            Skrivskyddad **int**. |
| [`hidden_slides`](/slides/python-net/sv/aspose.slides/documentproperties/hidden_slides/) | Returnerar antalet dolda bilder i ett presentationsdokument.<br/>            Skrivskyddad **int**. |
| [`notes`](/slides/python-net/sv/aspose.slides/documentproperties/notes/) | Returnerar antalet bilder i en presentation som innehåller anteckningar.<br/>            Skrivskyddad **int**. |
| [`paragraphs`](/slides/python-net/sv/aspose.slides/documentproperties/paragraphs/) | Returnerar det totala antalet stycken som finns i ett dokument om tillämpligt.<br/>            Skrivskyddad **int**. |
| [`words`](/slides/python-net/sv/aspose.slides/documentproperties/words/) | Returnerar det totala antalet ord som finns i ett dokument.<br/>            Skrivskyddad **int**. |
| [`multimedia_clips`](/slides/python-net/sv/aspose.slides/documentproperties/multimedia_clips/) | Returnerar det totala antalet ljud- eller videoklipp som finns i dokumentet.<br/>            Skrivskyddad **int**. |
| [`titles_of_parts`](/slides/python-net/sv/aspose.slides/documentproperties/titles_of_parts/) | Anger titeln för varje dokumentdel. <br/>            Dessa delar är inte dokumentdelar utan konceptuella representationer av dokumentsektioner.<br/>            Skrivskyddad **List[str]**. |
| [`heading_pairs`](/slides/python-net/sv/aspose.slides/documentproperties/heading_pairs/) | Anger gruppering av dokumentdelar och antalet delar i varje grupp.<br/>            Skrivskyddad **List[IHeadingPair]**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Hämtar ett namngivet booleskt värde från anpassade egenskaper. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Hämtar ett namngivet heltalsvärde från anpassade egenskaper. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Hämtar ett namngivet DateTime-värde från anpassade egenskaper. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Hämtar ett namngivet strängvärde från anpassade egenskaper. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | Anger en namngiven boolesk anpassad egenskap. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/set_custom_property_value/#str-int) | Anger en namngiven heltalsanpassad egenskap. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | Anger en namngiven DateTime-anpassad egenskap. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/set_custom_property_value/#str-str) | Anger en namngiven sträng-anpassad egenskap. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Anger en namngiven float-anpassad egenskap. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Anger en namngiven double-anpassad egenskap. |
| [`get_custom_property_name(self, index)`](/slides/python-net/sv/aspose.slides/documentproperties/get_custom_property_name/#int) | Returnerar ett anpassat egenskapsnamn på angivet index. |
| [`remove_custom_property(self, name)`](/slides/python-net/sv/aspose.slides/documentproperties/remove_custom_property/#str) | Tar bort en anpassad egenskap som är associerad med ett angivet namn. |
| [`contains_custom_property(self, name)`](/slides/python-net/sv/aspose.slides/documentproperties/contains_custom_property/#str) | Kontrollerar förekomsten av en anpassad egenskap med ett angivet namn. |
| [`clear_custom_properties(self)`](/slides/python-net/sv/aspose.slides/documentproperties/clear_custom_properties/#) | Tar bort alla anpassade egenskaper. |
| [`get_sensitivity_labels(self)`](/slides/python-net/sv/aspose.slides/documentproperties/get_sensitivity_labels/#) | Hämtar en array av känslighetsetiketter från anpassade dokumentegenskaper (Microsoft Information Protection SDK Metadata). |
| [`clear_built_in_properties(self)`](/slides/python-net/sv/aspose.slides/documentproperties/clear_built_in_properties/#) | Rensar och sätter standardvärden för alla inbyggda egenskaper. |
| [`clone(self)`](/slides/python-net/sv/aspose.slides/documentproperties/clone/#) | Klonar aktuellt objekt |
| [`clone_t(self)`](/slides/python-net/sv/aspose.slides/documentproperties/clone_t/#) | Klonar aktuellt objekt |

### Se även
* klass [`DocumentProperties`](/slides/python-net/sv/aspose.slides/documentproperties)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)