---
title: IDocumentProperties class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/idocumentproperties/
---
## IDocumentProperties klass

Representerar egenskaper för en presentation.

Typen IDocumentProperties exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`app_version`](/slides/python-net/sv/aspose.slides/idocumentproperties/app_version/) | Returnerar app-versionen.<br/>            Läs-endast **str**. |
| [`name_of_application`](/slides/python-net/sv/aspose.slides/idocumentproperties/name_of_application/) | Returnerar eller anger namnet på applikationen.<br/>            Läs/skriv **str**. |
| [`company`](/slides/python-net/sv/aspose.slides/idocumentproperties/company/) | Returnerar eller anger företags-egenskapen.<br/>            Läs/skriv **str**. |
| [`manager`](/slides/python-net/sv/aspose.slides/idocumentproperties/manager/) | Returnerar eller anger chefen-egenskapen.<br/>            Läs/skriv **str**. |
| [`presentation_format`](/slides/python-net/sv/aspose.slides/idocumentproperties/presentation_format/) | Returnerar eller anger det avsedda formatet för en presentation.<br/>            Läs/skriv **str**. |
| [`shared_doc`](/slides/python-net/sv/aspose.slides/idocumentproperties/shared_doc/) | Avgör om presentationen delas mellan flera personer.<br/>            Läs/skriv **bool**. |
| [`application_template`](/slides/python-net/sv/aspose.slides/idocumentproperties/application_template/) | Returnerar eller anger mallen för en applikation.<br/>            Läs/skriv **str**. |
| [`total_editing_time`](/slides/python-net/sv/aspose.slides/idocumentproperties/total_editing_time/) | Total redigeringstid för en presentation.<br/>            Läs/skriv **System.TimeSpan**. |
| [`title`](/slides/python-net/sv/aspose.slides/idocumentproperties/title/) | Returnerar eller anger titeln för en presentation.<br/>            Läs/skriv **str**. |
| [`subject`](/slides/python-net/sv/aspose.slides/idocumentproperties/subject/) | Returnerar eller anger ämnet för en presentation.<br/>            Läs/skriv **str**. |
| [`author`](/slides/python-net/sv/aspose.slides/idocumentproperties/author/) | Returnerar eller anger författaren till en presentation.<br/>            Läs/skriv **str**. |
| [`keywords`](/slides/python-net/sv/aspose.slides/idocumentproperties/keywords/) | Returnerar eller anger nyckelorden för en presentation.<br/>            Läs/skriv **str**. |
| [`comments`](/slides/python-net/sv/aspose.slides/idocumentproperties/comments/) | Returnerar eller anger kommentarer för en presentation.<br/>            Läs/skriv **str**. |
| [`category`](/slides/python-net/sv/aspose.slides/idocumentproperties/category/) | Returnerar eller anger kategorin för en presentation.<br/>            Läs/skriv **str**. |
| [`created_time`](/slides/python-net/sv/aspose.slides/idocumentproperties/created_time/) | Returnerar datumet då en presentation skapades.<br/>            Värdena är i UTC.<br/>            Läs/skriv **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/sv/aspose.slides/idocumentproperties/last_saved_time/) | Returnerar datumet då en presentation senast ändrades.<br/>            Värdena är i UTC.P<br/>            Läs-endast i fallet Presentation.DocumentProperties (eftersom den kommer att uppdateras internt under IPresentation-objektets sparprocess). <br/>            Kan ändras via DocumentProperties-instansen som returneras av metoden [`IPresentationInfo.read_document_properties`](/slides/python-net/sv/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Se exempel i **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** metodsammanfattning. |
| [`last_printed`](/slides/python-net/sv/aspose.slides/idocumentproperties/last_printed/) | Returnerar datumet då en presentation senast skrev ut.<br/>            Läs/skriv **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/sv/aspose.slides/idocumentproperties/last_saved_by/) | Returnerar eller anger namnet på den sista personen som ändrade en presentation.<br/>            Läs/skriv **str**. |
| [`revision_number`](/slides/python-net/sv/aspose.slides/idocumentproperties/revision_number/) | Returnerar eller anger presentationsrevisionsnumret.<br/>            Läs/skriv **int**. |
| [`content_status`](/slides/python-net/sv/aspose.slides/idocumentproperties/content_status/) | Returnerar eller anger innehållsstatusen för en presentation.<br/>            Läs/skriv **str**. |
| [`content_type`](/slides/python-net/sv/aspose.slides/idocumentproperties/content_type/) | Returnerar eller anger innehållstypen för en presentation.<br/>            Läs/skriv **str**. |
| [`hyperlink_base`](/slides/python-net/sv/aspose.slides/idocumentproperties/hyperlink_base/) | Returnerar eller anger dokumentegenskapen HyperlinkBase.<br/>            Läs/skriv **str**. |
| [`scale_crop`](/slides/python-net/sv/aspose.slides/idocumentproperties/scale_crop/) | Anger visningsläget för dokumentets miniatyr.<br/>            Sätt detta element till **true** för att aktivera skalning av miniatyren till visningen.<br/>            Sätt detta element till **false** för att aktivera beskärning av miniatyren så att endast sektioner som passar visningen visas.<br/>            Läs/skriv **bool**. |
| [`links_up_to_date`](/slides/python-net/sv/aspose.slides/idocumentproperties/links_up_to_date/) | Anger om hyperlänkar i ett dokument är aktuella.<br/>            Sätt detta element till **true** för att indikera att hyperlänkar är uppdaterade.<br/>            Sätt detta element till **false** för att indikera att hyperlänkar är föråldrade.<br/>            Läs/skriv **bool**. |
| [`hyperlinks_changed`](/slides/python-net/sv/aspose.slides/idocumentproperties/hyperlinks_changed/) | Specificerar att en eller flera hyperlänkar i denna del uppdaterades uteslutande i denna del av en producent.<br/>            Nästa producent som öppnar detta dokument ska uppdatera hyperlänkrelationerna med de nya hyperlänkarna som specificerats i denna del.<br/>            Läs/skriv **bool**. |
| [`slides`](/slides/python-net/sv/aspose.slides/idocumentproperties/slides/) | Anger det totala antalet bilder i ett presentationsdokument.<br/sv/>            Läs-endast **int**. |
| [`hidden_slides`](/slides/python-net/sv/aspose.slides/idocumentproperties/hidden_slides/) | Anger antalet dolda bilder i ett presentationsdokument.<br/>            Läs-endast **int**. |
| [`notes`](/slides/python-net/sv/aspose.slides/idocumentproperties/notes/) | Anger antalet bilder i en presentation som innehåller anteckningar.<br/>            Läs-endast **int**. |
| [`paragraphs`](/slides/python-net/sv/aspose.slides/idocumentproperties/paragraphs/) | Anger det totala antalet stycken som finns i ett dokument, om tillämpligt.<br/>            Läs-endast **int**. |
| [`words`](/slides/python-net/sv/aspose.slides/idocumentproperties/words/) | Anger det totala antalet ord i ett dokument.<br/>            Läs-endast **int**. |
| [`multimedia_clips`](/slides/python-net/sv/aspose.slides/idocumentproperties/multimedia_clips/) | Anger det totala antalet ljud- eller videoklipp som finns i dokumentet.<br/>            Läs-endast **int**. |
| [`titles_of_parts`](/slides/python-net/sv/aspose.slides/idocumentproperties/titles_of_parts/) | Anger titeln för varje dokumentdel.<br/>            Dessa delar är inte dokumentdelar utan konceptuella representationer av dokumentsektioner.<br/>            Läs-endast **List[str]**. |
| [`heading_pairs`](/slides/python-net/sv/aspose.slides/idocumentproperties/heading_pairs/) | Anger gruppering av dokumentdelar och antalet delar i varje grupp.<br/>            Läs-endast **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/sv/aspose.slides/idocumentproperties/count_of_custom_properties/) | Returnerar antalet anpassade egenskaper som faktiskt finns i en samling.<br/>            Läs-endast **int**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Hämtar ett namngivet booleskt värde från de anpassade egenskaperna. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Hämtar ett namngivet heltalsvärde från de anpassade egenskaperna. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Hämtar ett namngivet DateTime-värde från de anpassade egenskaperna. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Hämtar ett namngivet strängvärde från de anpassade egenskaperna. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Anger en namngiven boolesk anpassad egenskap. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Anger en namngiven heltals-anpassad egenskap. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Anger en namngiven DateTime-anpassad egenskap. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Anger en namngiven sträng-anpassad egenskap. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Anger en namngiven float-anpassad egenskap. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/sv/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Anger en namngiven double-anpassad egenskap. |
| [`get_custom_property_name(self, index)`](/slides/python-net/sv/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Returnerar ett anpassat egenskapsnamn på det angivna indexet. |
| [`remove_custom_property(self, name)`](/slides/python-net/sv/aspose.slides/idocumentproperties/remove_custom_property/#str) | Tar bort en anpassad egenskap som är associerad med ett angivet namn. |
| [`contains_custom_property(self, name)`](/slides/python-net/sv/aspose.slides/idocumentproperties/contains_custom_property/#str) | Kontrollerar förekomsten av en anpassad egenskap med ett angivet namn. |
| [`clear_custom_properties(self)`](/slides/python-net/sv/aspose.slides/idocumentproperties/clear_custom_properties/#) | Tar bort alla anpassade egenskaper. |
| [`clear_built_in_properties(self)`](/slides/python-net/sv/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Rensar och sätter standardvärden för alla inbyggda egenskaper. |
| [`get_sensitivity_labels(self)`](/slides/python-net/sv/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Hämtar en array av känslighetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata). |

### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)