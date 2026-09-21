---
title: DocumentProperties class
second_title: Aspose.Slides voor Python via .NET API-referentie
description:
type: docs
url: /nl/aspose.slides/documentproperties/
---
## DocumentProperties klasse

Stelt de eigenschappen van een presentatie voor.

Het type DocumentProperties biedt de volgende leden weer:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides/documentproperties/__init__/#) | Initialiseert een nieuw exemplaar van klasse [`DocumentProperties`](/slides/python-net/nl/aspose.slides/documentproperties). |

## Properties

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/nl/aspose.slides/documentproperties/app_version/) | Geeft de app-versie terug.<br/>            Alleen-lezen **str**. |
| [`name_of_application`](/slides/python-net/nl/aspose.slides/documentproperties/name_of_application/) | Geeft de naam van de applicatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`company`](/slides/python-net/nl/aspose.slides/documentproperties/company/) | Geeft de bedrijfs-eigenschap terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`manager`](/slides/python-net/nl/aspose.slides/documentproperties/manager/) | Geeft de manager-eigenschap terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`presentation_format`](/slides/python-net/nl/aspose.slides/documentproperties/presentation_format/) | Geeft het beoogde formaat van een presentatie terug of stelt dit in.<br/>            Lezen/Schrijven **str**. |
| [`shared_doc`](/slides/python-net/nl/aspose.slides/documentproperties/shared_doc/) | Bepaalt of de presentatie gedeeld wordt tussen meerdere personen.<br/>            Lezen/Schrijven **bool**. |
| [`application_template`](/slides/python-net/nl/aspose.slides/documentproperties/application_template/) | Geeft de sjabloon van een applicatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`total_editing_time`](/slides/python-net/nl/aspose.slides/documentproperties/total_editing_time/) | Totale bewerkingstijd van een presentatie.<br/>            Lezen/Schrijven **System.TimeSpan**. |
| [`title`](/slides/python-net/nl/aspose.slides/documentproperties/title/) | Geeft de titel van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`subject`](/slides/python-net/nl/aspose.slides/documentproperties/subject/) | Geeft het onderwerp van een presentatie terug of stelt dit in.<br/>            Lezen/Schrijven **str**. |
| [`author`](/slides/python-net/nl/aspose.slides/documentproperties/author/) | Geeft de auteur van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`keywords`](/slides/python-net/nl/aspose.slides/documentproperties/keywords/) | Geeft de trefwoorden van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`comments`](/slides/python-net/nl/aspose.slides/documentproperties/comments/) | Geeft de opmerkingen van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`category`](/slides/python-net/nl/aspose.slides/documentproperties/category/) | Geeft de categorie van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`created_time`](/slides/python-net/nl/aspose.slides/documentproperties/created_time/) | Geeft de datum waarop een presentatie is aangemaakt terug.<br/>            Waarden zijn in UTC.<br/>            Lezen/Schrijven **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/nl/aspose.slides/documentproperties/last_saved_time/) | Geeft de datum waarop een presentatie voor het laatst is gewijzigd terug.<br/>            Waarden zijn in UTC.<br/>            Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). <br/>            Kan worden gewijzigd via een DocumentProperties-instantie die wordt geretourneerd door methode [`IPresentationInfo.read_document_properties`](/slides/python-net/nl/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Zie het voorbeeld in **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**-samenvatting. |
| [`last_printed`](/slides/python-net/nl/aspose.slides/documentproperties/last_printed/) | Geeft de datum waarop een presentatie voor het laatst is afgedrukt terug.<br/>            Lezen/Schrijven **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/nl/aspose.slides/documentproperties/last_saved_by/) | Geeft de naam van de laatste persoon die een presentatie heeft gewijzigd terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`revision_number`](/slides/python-net/nl/aspose.slides/documentproperties/revision_number/) | Geeft het revisienummer van de presentatie terug of stelt dit in.<br/>            Lezen/Schrijven **int**. |
| [`content_status`](/slides/python-net/nl/aspose.slides/documentproperties/content_status/) | Geeft de inhoudsstatus van een presentatie terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`content_type`](/slides/python-net/nl/aspose.slides/documentproperties/content_type/) | Geeft het inhoudstype van een presentatie terug of stelt dit in.<br/>            Lezen/Schrijven **str**. |
| [`hyperlink_base`](/slides/python-net/nl/aspose.slides/documentproperties/hyperlink_base/) | Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`count_of_custom_properties`](/slides/python-net/nl/aspose.slides/documentproperties/count_of_custom_properties/) | Geeft het aantal aangepaste eigenschappen dat daadwerkelijk in de collectie zit terug.<br/>            Alleen-lezen **int**. |
| [`scale_crop`](/slides/python-net/nl/aspose.slides/documentproperties/scale_crop/) | Geeft de weergavemodus van de miniatuur van het document aan. <br/>            Stel dit element in op **true**  om schalen van de miniatuur naar het scherm in te schakelen. <br/>            Stel dit element in op **false**  om bijsnijden van de miniatuur in te schakelen zodat alleen secties die op het scherm passen worden getoond.<br/>            Lezen/Schrijven **bool**. |
| [`links_up_to_date`](/slides/python-net/nl/aspose.slides/documentproperties/links_up_to_date/) | Geeft aan of hyperlinks in een document actueel zijn. <br/>            Stel dit element in op **true**  om aan te geven dat hyperlinks zijn bijgewerkt. <br/>            Stel dit element in op **false**  om aan te geven dat hyperlinks verouderd zijn.<br/>            Lezen/Schrijven **bool**. |
| [`hyperlinks_changed`](/slides/python-net/nl/aspose.slides/documentproperties/hyperlinks_changed/) | Geeft aan dat één of meer hyperlinks in dit deel uitsluitend in dit deel door een producer zijn bijgewerkt. <br/>            De volgende producer die dit document opent, dient de hyperlink-relaties bij te werken met de nieuwe hyperlinks die in dit deel zijn opgegeven.<br/>            Lezen/Schrijven **bool**. |
| [`slides`](/slides/python-net/nl/aspose.slides/documentproperties/slides/) | Geeft het totale aantal dia’s in een presentatiedocument terug.<br/nl/>            Alleen-lezen **int**. |
| [`hidden_slides`](/slides/python-net/nl/aspose.slides/documentproperties/hidden_slides/) | Geeft het aantal verborgen dia’s in een presentatiedocument terug.<br/>            Alleen-lezen **int**. |
| [`notes`](/slides/python-net/nl/aspose.slides/documentproperties/notes/) | Geeft het aantal dia’s in een presentatie met notities terug.<br/>            Alleen-lezen **int**. |
| [`paragraphs`](/slides/python-net/nl/aspose.slides/documentproperties/paragraphs/) | Geeft het totale aantal alinea’s dat in een document is gevonden, indien van toepassing, terug.<br/>            Alleen-lezen **int**. |
| [`words`](/slides/python-net/nl/aspose.slides/documentproperties/words/) | Geeft het totale aantal woorden dat in een document staat terug.<br/>            Alleen-lezen **int**. |
| [`multimedia_clips`](/slides/python-net/nl/aspose.slides/documentproperties/multimedia_clips/) | Geeft het totale aantal geluids- of videoclips dat in het document aanwezig is terug.<br/>            Alleen-lezen **int**. |
| [`titles_of_parts`](/slides/python-net/nl/aspose.slides/documentproperties/titles_of_parts/) | Specificeert de titel van elk documentonderdeel. <br/>            Deze onderdelen zijn geen documentonderdelen, maar conceptuele weergaven van documentsecties.<br/>            Alleen-lezen **List[str]**. |
| [`heading_pairs`](/slides/python-net/nl/aspose.slides/documentproperties/heading_pairs/) | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan.<br/>            Alleen-lezen **List[IHeadingPair]**. |

## Methods

| Method | Description |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Haalt een benoemde bool-waarde op uit de aangepaste eigenschappen. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Haalt een benoemde gehele-waarde op uit de aangepaste eigenschappen. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Haalt een benoemde tekenreeks-waarde op uit de aangepaste eigenschappen. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | Stelt een benoemde bool-aangepaste eigenschap in. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/set_custom_property_value/#str-int) | Stelt een benoemde gehele-aangepaste eigenschap in. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | Stelt een benoemde DateTime-aangepaste eigenschap in. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/set_custom_property_value/#str-str) | Stelt een benoemde tekenreeks-aangepaste eigenschap in. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Stelt een benoemde float-aangepaste eigenschap in. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/nl/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Stelt een benoemde double-aangepaste eigenschap in. |
| [`get_custom_property_name(self, index)`](/slides/python-net/nl/aspose.slides/documentproperties/get_custom_property_name/#int) | Retourneert een aangepaste eigenschapsnaam op de opgegeven index. |
| [`remove_custom_property(self, name)`](/slides/python-net/nl/aspose.slides/documentproperties/remove_custom_property/#str) | Verwijdert een aangepaste eigenschap die gekoppeld is aan een opgegeven naam. |
| [`contains_custom_property(self, name)`](/slides/python-net/nl/aspose.slides/documentproperties/contains_custom_property/#str) | Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [`clear_custom_properties(self)`](/slides/python-net/nl/aspose.slides/documentproperties/clear_custom_properties/#) | Verwijdert alle aangepaste eigenschappen. |
| [`get_sensitivity_labels(self)`](/slides/python-net/nl/aspose.slides/documentproperties/get_sensitivity_labels/#) | Haalt een array van gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK-metadata). |
| [`clear_built_in_properties(self)`](/slides/python-net/nl/aspose.slides/documentproperties/clear_built_in_properties/#) | Wis en stel standaardwaarden in voor alle ingebouwde eigenschappen. |
| [`clone(self)`](/slides/python-net/nl/aspose.slides/documentproperties/clone/#) | Kloont het huidige object |
| [`clone_t(self)`](/slides/python-net/nl/aspose.slides/documentproperties/clone_t/#) | Kloont het huidige object |

### Zie ook
* class [`DocumentProperties`](/slides/python-net/nl/aspose.slides/documentproperties)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)