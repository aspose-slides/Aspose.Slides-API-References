---
title: Presentation class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/presentation/
---
## Presentation klasse

Stelt een Microsoft PowerPoint-presentatie voor.

The Presentation type exposes the following members:

## Constructors

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#) | Deze constructor maakt een nieuwe presentatie vanaf nul.<br/>            De gemaakte presentatie heeft één lege dia. |
| [`__init__(self, load_options)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#loadoptions) | Deze constructor maakt een nieuwe presentatie vanaf nul.<br/>            De gemaakte presentatie heeft één lege dia. |
| [`__init__(self, stream)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#iorawiobase) | Deze constructor is de primaire methode voor het lezen van een bestaande Presentation. |
| [`__init__(self, stream, load_options)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Deze constructor is de primaire methode voor het lezen van een bestaande Presentation. |
| [`__init__(self, file)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#str) | Deze constructor krijgt een bronbestandspad van waaruit<br/>             de inhoud van de Presentation wordt gelezen. |
| [`__init__(self, file, load_options)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#str-loadoptions) | Deze constructor krijgt een bronbestandspad van waaruit<br/>            de inhoud van de Presentation wordt gelezen. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`current_date_time`](/slides/python-net/nl/aspose.slides/presentation/current_date_time/) | Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen.<br/>            Tijd van creatie van dit Presentation-object standaard.<br/>            Read/write **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/nl/aspose.slides/presentation/header_footer_manager/) | Retourneert de daadwerkelijke HeaderFooter-beheerder.<br/>            Read-only [`IPresentationHeaderFooterManager`](/slides/python-net/nl/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/nl/aspose.slides/presentation/protection_manager/) | Verkrijgt beheerder van de permissies voor deze presentatie.<br/>            Read-only [`IProtectionManager`](/slides/python-net/nl/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/nl/aspose.slides/presentation/slides/) | Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd.<br/nl/>            Read-only [`ISlideCollection`](/slides/python-net/nl/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/nl/aspose.slides/presentation/sections/) | Retourneert een lijst van alle secties van dia's die in de presentatie zijn gedefinieerd.<br/>            Read-only [`ISectionCollection`](/slides/python-net/nl/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/nl/aspose.slides/presentation/slide_size/) | Retourneert slide-size-object.<br/>            Read-only [`ISlideSize`](/slides/python-net/nl/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/nl/aspose.slides/presentation/notes_size/) | Retourneert notitie-dia-size-object.<br/>            Read-only [`INotesSize`](/slides/python-net/nl/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/nl/aspose.slides/presentation/layout_slides/) | Retourneert een lijst van alle lay-outdia's die in de presentatie zijn gedefinieerd.<br/>            Read-only [`IGlobalLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/nl/aspose.slides/presentation/masters/) | Retourneert een lijst van alle masterdia's die in de presentatie zijn gedefinieerd.<br/>            Read-only [`IMasterSlideCollection`](/slides/python-net/nl/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/nl/aspose.slides/presentation/master_notes_slide_manager/) | Retourneert notitie-masterbeheerder.<br/>            Read-only [`IMasterNotesSlideManager`](/slides/python-net/nl/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/nl/aspose.slides/presentation/master_handout_slide_manager/) | Retourneert hand-out masterbeheerder.<br/>            Read-only [`IMasterHandoutSlideManager`](/slides/python-net/nl/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/nl/aspose.slides/presentation/fonts_manager/) | Retourneert lettertypebeheerder.<br/>            Read-only [`IFontsManager`](/slides/python-net/nl/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/nl/aspose.slides/presentation/default_text_style/) | Retourneert de standaard tekststijl voor shapes.<br/>            Read-only [`ITextStyle`](/slides/python-net/nl/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/nl/aspose.slides/presentation/comment_authors/) | Retourneert de collectie van commentaarauteurs.<br/>            Read-only [`ICommentAuthorCollection`](/slides/python-net/nl/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/nl/aspose.slides/presentation/document_properties/) | Retourneert DocumentProperties-object dat standaard en aangepaste documenteigenschappen bevat.<br/>            Read-only [`IDocumentProperties`](/slides/python-net/nl/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/nl/aspose.slides/presentation/images/) | Retourneert de collectie van alle afbeeldingen in de presentatie.<br/>            Read-only [`IImageCollection`](/slides/python-net/nl/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/nl/aspose.slides/presentation/audios/) | Retourneert de collectie van alle ingebedde audiobestanden in de presentatie.<br/>            Read-only [`IAudioCollection`](/slides/python-net/nl/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/nl/aspose.slides/presentation/videos/) | Retourneert de collectie van alle ingebedde videobestanden in de presentatie.<br/>            Read-only [`IVideoCollection`](/slides/python-net/nl/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/nl/aspose.slides/presentation/slide_show_settings/) | Retourneert de diavoorstellinginstellingen voor de presentatie. |
| [`digital_signatures`](/slides/python-net/nl/aspose.slides/presentation/digital_signatures/) | Retourneert de collectie van handtekeningen die gebruikt werden om de presentatie te ondertekenen.<br/>            Read-only [`IDigitalSignatureCollection`](/slides/python-net/nl/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/presentation/custom_data/) | Retourneert de aangepaste gegevens van de presentatie.<br/>            Read-only [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/nl/aspose.slides/presentation/all_custom_xml_parts/) | Retourneert alle aangepaste gegevensonderdelen in de presentatie.<br/>            Read-only [`ICustomXmlPart`](/slides/python-net/nl/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/nl/aspose.slides/presentation/vba_project/) | Verkrijgt of stelt VBA-project met presentatie-macro's in.<br/>            Read/write [`IVbaProject`](/slides/python-net/nl/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/presentation/hyperlink_queries/) | Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatiedia's staan (niet in master-, lay-out- of notitiesdia's).<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/nl/aspose.slides/presentation/view_properties/) | Verkrijgt breedtoepassende weergave-eigenschappen van de presentatie.<br/>            Read-only [`IViewProperties`](/slides/python-net/nl/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/nl/aspose.slides/presentation/first_slide_number/) | Stelt het eerste dia-nummer in de presentatie voor |
| [`sensitivity_labels`](/slides/python-net/nl/aspose.slides/presentation/sensitivity_labels/) | Retourneert de collectie van gevoeligheidslabels die op het presentatiedocument zijn toegepast.<br/>            Read-only [`ISensitivityLabelCollection`](/slides/python-net/nl/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/nl/aspose.slides/presentation/source_format/) | Retourneert informatie over vanuit welk formaat de presentatie is geladen.<br/>            Read-only [`SourceFormat`](/slides/python-net/nl/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/nl/aspose.slides/presentation/master_theme/) | Retourneert master-thema.<br/>            Read-only [`IMasterTheme`](/slides/python-net/nl/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/nl/aspose.slides/presentation/presentation/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/nl/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Slaat alle dia's van een presentatie op naar een bestand met het opgegeven formaat. |
| [`save(self, stream, format)`](/slides/python-net/nl/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Slaat alle dia's van een presentatie op naar een stream in het opgegeven formaat. |
| [`save(self, fname, format, options)`](/slides/python-net/nl/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/nl/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Slaat alle dia's van een presentatie op naar een stream in het opgegeven formaat met extra opties. |
| [`save(self, options)`](/slides/python-net/nl/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Slaat alle dia's van een presentatie op naar een reeks bestanden die XAML-opmaak voorstellen. |
| [`save(self, fname, slides, format)`](/slides/python-net/nl/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Slaat opgegeven dia's van een presentatie op naar een bestand met het opgegeven formaat met behoud van paginanummer. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/nl/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Slaat opgegeven dia's van een presentatie op naar een bestand met het opgegeven formaat met behoud van paginanummer. |
| [`save(self, stream, slides, format)`](/slides/python-net/nl/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Slaat opgegeven dia's van een presentatie op naar een stream in het opgegeven formaat met behoud van paginanummer. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/nl/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Slaat opgegeven dia's van een presentatie op naar een stream in het opgegeven formaat met behoud van paginanummer. |
| [`get_images(self, options)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Retourneert Image-objecten voor alle dia's van een presentatie. |
| [`get_images(self, options, slides)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Retourneert Thumbnail Image-objecten voor opgegeven dia's van een presentatie. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie met aangepaste schaal. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Retourneert Thumbnail Image-objecten voor opgegeven dia's van een presentatie met aangepaste schaal. |
| [`get_images(self, options, image_size)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie met opgegeven grootte. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Retourneert Thumbnail Image-objecten voor opgegeven dia's van een presentatie met opgegeven grootte. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/nl/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/nl/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`get_slide_by_id(self, id)`](/slides/python-net/nl/aspose.slides/presentation/get_slide_by_id/#int) | Retourneert een Slide, MasterSlide of LayoutSlide op Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/presentation/join_portions_with_same_formatting/#) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele shapes in alle dia's. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/nl/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/nl/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/nl/aspose.slides/presentation/replace_regex/#str-str) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)