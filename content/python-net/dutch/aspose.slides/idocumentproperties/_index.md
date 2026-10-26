---
title: IDocumentProperties class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/idocumentproperties/
---
## IDocumentProperties klasse

Vertegenwoordigt eigenschappen van een presentatie.

Het IDocumentProperties-type geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`app_version`](/slides/python-net/nl/aspose.slides/idocumentproperties/app_version/) | Geeft de appversie terug.<br/>            Alleen-lezen **str**. |
| [`name_of_application`](/slides/python-net/nl/aspose.slides/idocumentproperties/name_of_application/) | Geeft de naam van de applicatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`company`](/slides/python-net/nl/aspose.slides/idocumentproperties/company/) | Geeft de bedrijfs eigenschap terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`manager`](/slides/python-net/nl/aspose.slides/idocumentproperties/manager/) | Geeft de manager-eigenschap terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`presentation_format`](/slides/python-net/nl/aspose.slides/idocumentproperties/presentation_format/) | Geeft het beoogde formaat van een presentatie terug of stelt dit in.<br/>            Lezen/Schrijven **str**. |
| [`shared_doc`](/slides/python-net/nl/aspose.slides/idocumentproperties/shared_doc/) | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen.<br/>            Lezen/Schrijven **bool**. |
| [`application_template`](/slides/python-net/nl/aspose.slides/idocumentproperties/application_template/) | Geeft het sjabloon van een applicatie terug of stelt dit in.<br/>            Lezen/Schrijven **str**. |
| [`total_editing_time`](/slides/python-net/nl/aspose.slides/idocumentproperties/total_editing_time/) | Totale bewerkingstijd van een presentatie.<br/>            Lezen/Schrijven **System.TimeSpan**. |
| [`title`](/slides/python-net/nl/aspose.slides/idocumentproperties/title/) | Geeft de titel van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`subject`](/slides/python-net/nl/aspose.slides/idocumentproperties/subject/) | Geeft het onderwerp van een presentatie terug of stelt dit in.<br/>            Lezen/Schrijven **str**. |
| [`author`](/slides/python-net/nl/aspose.slides/idocumentproperties/author/) | Geeft de auteur van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`keywords`](/slides/python-net/nl/aspose.slides/idocumentproperties/keywords/) | Geeft de trefwoorden van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`comments`](/slides/python-net/nl/aspose.slides/idocumentproperties/comments/) | Geeft de opmerkingen van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`category`](/slides/python-net/nl/aspose.slides/idocumentproperties/category/) | Geeft de categorie van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`created_time`](/slides/python-net/nl/aspose.slides/idocumentproperties/created_time/) | Geeft de datum terug waarop een presentatie is gemaakt.<br/>            Waarden zijn in UTC.<br/>            Lezen/Schrijven **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/nl/aspose.slides/idocumentproperties/last_saved_time/) | Geeft de datum terug waarop een presentatie voor het laatst is gewijzigd.<br/>            Waarden zijn in UTC.P<br/>            Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). <br/>            Kan worden gewijzigd via het DocumentProperties-instance dat wordt geretourneerd door methode [`IPresentationInfo.read_document_properties`](/slides/python-net/nl/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Zie het voorbeeld in **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** method summary. |
| [`last_printed`](/slides/python-net/nl/aspose.slides/idocumentproperties/last_printed/) | Geeft de datum terug waarop een presentatie voor het laatst is afgedrukt.<br/>            Lezen/Schrijven **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/nl/aspose.slides/idocumentproperties/last_saved_by/) | Geeft de naam terug of stelt deze in van de laatste persoon die een presentatie heeft aangepast.<br/>            Lezen/Schrijven **str**. |
| [`revision_number`](/slides/python-net/nl/aspose.slides/idocumentproperties/revision_number/) | Geeft het revisienummer van de presentatie terug of stelt dit in.<br/>            Lezen/Schrijven **int**. |
| [`content_status`](/slides/python-net/nl/aspose.slides/idocumentproperties/content_status/) | Geeft de contentstatus van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`content_type`](/slides/python-net/nl/aspose.slides/idocumentproperties/content_type/) | Geeft het contenttype van een presentatie terug of stelt dit in.<br/>            Lezen/Schrijven **str**. |
| [`hyperlink_base`](/slides/python-net/nl/aspose.slides/idocumentproperties/hyperlink_base/) | Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`scale_crop`](/slides/python-net/nl/aspose.slides/idocumentproperties/scale_crop/) | Geeft de weergavemodus van de document-miniatuur aan.<br/>            Zet dit element op **true** om het schalen van de document-miniatuur naar het scherm in te schakelen.<br/>            Zet dit element op **false** om bijsnijden van de document-miniatuur in te schakelen zodat alleen secties die op het scherm passen worden getoond.<br/>            Lezen/Schrijven **bool**. |
| [`links_up_to_date`](/slides/python-net/nl/aspose.slides/idocumentproperties/links_up_to_date/) | Geeft aan of hyperlinks in een document actueel zijn.<br/>            Zet dit element op **true** om aan te geven dat hyperlinks zijn bijgewerkt.<br/>            Zet dit element op **false** om aan te geven dat hyperlinks verouderd zijn.<br/>            Lezen/Schrijven **bool**. |
| [`hyperlinks_changed`](/slides/python-net/nl/aspose.slides/idocumentproperties/hyperlinks_changed/) | Specificeert dat een of meer hyperlinks in dit deel uitsluitend in dit deel door een producer zijn bijgewerkt.<br/>            De volgende producer die dit document opent, moet de hyperlink-relaties bijwerken met de nieuwe hyperlinks die in dit deel zijn gespecificeerd.<br/>            Lezen/Schrijven **bool**. |
| [`slides`](/slides/python-net/nl/aspose.slides/idocumentproperties/slides/) | Specificeert het totale aantal dia's in een presentatiedocument.<br/nl/>            Alleen-lezen **int**. |
| [`hidden_slides`](/slides/python-net/nl/aspose.slides/idocumentproperties/hidden_slides/) | Specificeert het aantal verborgen dia's in een presentatiedocument.<br/>            Alleen-lezen **int**. |
| [`notes`](/slides/python-net/nl/aspose.slides/idocumentproperties/notes/) | Specificeert het aantal dia's in een presentatie dat notities bevat.<br/>            Alleen-lezen **int**. |
| [`paragraphs`](/slides/python-net/nl/aspose.slides/idocumentproperties/paragraphs/) | Specificeert het totale aantal alinea's dat in een document is gevonden, indien van toepassing.<br/>            Alleen-lezen **int**. |
| [`words`](/slides/python-net/nl/aspose.slides/idocumentproperties/words/) | Specificeert het totale aantal woorden dat in een document staat.<br/>            Alleen-lezen **int**. |
| [`multimedia_clips`](/slides/python-net/nl/aspose.slides/idocumentproperties/multimedia_clips/) | Specificeert het totale aantal geluids- of videoclips dat in het document aanwezig is.<br/>            Alleen-lezen **int**. |
| [`titles_of_parts`](/slides/python-net/nl/aspose.slides/idocumentproperties/titles_of_parts/) | Specificeert de titel van elk documentdeel.<br/>            Deze delen zijn geen documentdelen maar conceptuele weergaven van documentsecties.<br/>            Alleen-lezen **List[str]**. |
| [`heading_pairs`](/slides/python-net/nl/aspose.slides/idocumentproperties/heading_pairs/) | Geeft de groepering van documentdelen en het aantal delen in elke groep aan.<br/>            Alleen-lezen **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/nl/aspose.slides/idocumentproperties/count_of_custom_properties/) | Geeft het aantal aangepaste eigenschappen dat werkelijk in een collectie is opgenomen terug.<br/>            Alleen-lezen **int**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Haalt een benoemde gehele getalwaarde op uit de aangepaste eigenschappen. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Haalt een benoemde tekenreekswaarde op uit de aangepaste eigenschappen. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Stelt een benoemde booleaanse aangepaste eigenschap in. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Stelt een benoemde gehele aangepaste eigenschap in. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Stelt een benoemde DateTime-aangepaste eigenschap in. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Stelt een benoemde tekenreeks-aangepaste eigenschap in. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Stelt een benoemde float-aangepaste eigenschap in. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Stelt een benoemde double-aangepaste eigenschap in. |
| [`get_custom_property_name(self, index)`](/slides/python-net/nl/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Retourneert een aangepaste eigenschapsnaam op de opgegeven index. |
| [`remove_custom_property(self, name)`](/slides/python-net/nl/aspose.slides/idocumentproperties/remove_custom_property/#str) | Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld. |
| [`contains_custom_property(self, name)`](/slides/python-net/nl/aspose.slides/idocumentproperties/contains_custom_property/#str) | Controleert of een aangepaste eigenschap met een opgegeven naam aanwezig is. |
| [`clear_custom_properties(self)`](/slides/python-net/nl/aspose.slides/idocumentproperties/clear_custom_properties/#) | Verwijdert alle aangepaste eigenschappen. |
| [`clear_built_in_properties(self)`](/slides/python-net/nl/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Wis en stel standaardwaarden in voor alle ingebouwde eigenschappen. |
| [`get_sensitivity_labels(self)`](/slides/python-net/nl/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Haalt een array van gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata). |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)