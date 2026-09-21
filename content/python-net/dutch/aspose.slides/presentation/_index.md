---
title: Presentation class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/presentation/
---
## Presentation klasse

Stelt een Microsoft PowerPoint-presentatie voor.

Het type Presentation biedt de volgende leden weer:

## Constructoren

| Constructor | Omschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#) | Deze constructor maakt een nieuwe presentatie vanaf nul aan.<br/>            De gemaakte presentatie heeft één lege dia. |
| [`__init__(self, load_options)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#loadoptions) | Deze constructor maakt een nieuwe presentatie vanaf nul aan.<br/>            De gemaakte presentatie heeft één lege dia. |
| [`__init__(self, stream)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#iorawiobase) | Deze constructor is de primaire methode om een bestaande Presentation te lezen. |
| [`__init__(self, stream, load_options)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Deze constructor is de primaire methode om een bestaande Presentation te lezen. |
| [`__init__(self, file)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#str) | Deze constructor krijgt een bronbestandspad vanwaar<br/>            de inhoud van de Presentation wordt gelezen. |
| [`__init__(self, file, load_options)`](/slides/python-net/nl/aspose.slides/presentation/__init__/#str-loadoptions) | Deze constructor krijgt een bronbestandspad vanwaar<br/>            de inhoud van de Presentation wordt gelezen. |

## Eigenschappen

| Eigenschap | Omschrijving |
| :- | :- |
| [`current_date_time`](/slides/python-net/nl/aspose.slides/presentation/current_date_time/) | Geeft datum en tijd terug of stelt deze in die de inhoud van datum-tijdvelden zal vervangen.<br/>            Tijd van het maken van dit Presentation-object standaard.<br/>            Lezen/schrijven **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/nl/aspose.slides/presentation/header_footer_manager/) | Geeft de actuele HeaderFooter-manager terug.<br/>            Alleen-lezen [`IPresentationHeaderFooterManager`](/slides/python-net/nl/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/nl/aspose.slides/presentation/protection_manager/) | Haalt de manager van de permissies voor deze presentatie op.<br/>            Alleen-lezen [`IProtectionManager`](/slides/python-net/nl/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/nl/aspose.slides/presentation/slides/) | Geeft een lijst van alle dia's die in de presentatie zijn gedefinieerd.<br/nl/>            Alleen-lezen [`ISlideCollection`](/slides/python-net/nl/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/nl/aspose.slides/presentation/sections/) | Geeft een lijst van alle secties van dia's die in de presentatie zijn gedefinieerd.<br/>            Alleen-lezen [`ISectionCollection`](/slides/python-net/nl/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/nl/aspose.slides/presentation/slide_size/) | Geeft het dia-grootteobject terug.<br/>            Alleen-lezen [`ISlideSize`](/slides/python-net/nl/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/nl/aspose.slides/presentation/notes_size/) | Geeft het notities-dia-grootteobject terug.<br/>            Alleen-lezen [`INotesSize`](/slides/python-net/nl/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/nl/aspose.slides/presentation/layout_slides/) | Geeft een lijst van alle lay-out-dia's die in de presentatie zijn gedefinieerd.<br/>            Alleen-lezen [`IGlobalLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/nl/aspose.slides/presentation/masters/) | Geeft een lijst van alle master-dia's die in de presentatie zijn gedefinieerd.<br/>            Alleen-lezen [`IMasterSlideCollection`](/slides/python-net/nl/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/nl/aspose.slides/presentation/master_notes_slide_manager/) | Geeft de notities-master-manager terug.<br/>            Alleen-lezen [`IMasterNotesSlideManager`](/slides/python-net/nl/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/nl/aspose.slides/presentation/master_handout_slide_manager/) | Geeft de hand-out-master-manager terug.<br/>            Alleen-lezen [`IMasterHandoutSlideManager`](/slides/python-net/nl/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/nl/aspose.slides/presentation/fonts_manager/) | Geeft de lettertype-manager terug.<br/>            Alleen-lezen [`IFontsManager`](/slides/python-net/nl/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/nl/aspose.slides/presentation/default_text_style/) | Geeft de standaard tekststijl voor vormen terug.<br/>            Alleen-lezen [`ITextStyle`](/slides/python-net/nl/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/nl/aspose.slides/presentation/comment_authors/) | Geeft de verzameling van commentaarauteurs terug.<br/>            Alleen-lezen [`ICommentAuthorCollection`](/slides/python-net/nl/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/nl/aspose.slides/presentation/document_properties/) | Geeft een DocumentProperties-object terug dat standaard- en aangepaste documenteigenschappen bevat.<br/>            Alleen-lezen [`IDocumentProperties`](/slides/python-net/nl/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/nl/aspose.slides/presentation/images/) | Geeft de verzameling van alle afbeeldingen in de presentatie terug.<br/>            Alleen-lezen [`IImageCollection`](/slides/python-net/nl/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/nl/aspose.slides/presentation/audios/) | Geeft de verzameling van alle ingebedde audiobestanden in de presentatie terug.<br/>            Alleen-lezen [`IAudioCollection`](/slides/python-net/nl/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/nl/aspose.slides/presentation/videos/) | Geeft de verzameling van alle ingebedde videobestanden in de presentatie terug.<br/>            Alleen-lezen [`IVideoCollection`](/slides/python-net/nl/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/nl/aspose.slides/presentation/slide_show_settings/) | Geeft de diavoorstelling-instellingen voor de presentatie terug. |
| [`digital_signatures`](/slides/python-net/nl/aspose.slides/presentation/digital_signatures/) | Geeft de verzameling van handtekeningen die worden gebruikt om de presentatie te ondertekenen terug.<br/>            Alleen-lezen [`IDigitalSignatureCollection`](/slides/python-net/nl/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/presentation/custom_data/) | Geeft de aangepaste gegevens van de presentatie terug.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/nl/aspose.slides/presentation/all_custom_xml_parts/) | Geeft alle aangepaste gegevensonderdelen in de presentatie terug.<br/>            Alleen-lezen [`ICustomXmlPart`](/slides/python-net/nl/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/nl/aspose.slides/presentation/vba_project/) | Haalt of stelt het VBA-project met presentatiemacro's in.<br/>            Lezen/schrijven [`IVbaProject`](/slides/python-net/nl/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/presentation/hyperlink_queries/) | Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatiedia's staan (niet in master-, lay-out- of notitiedia's).<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/nl/aspose.slides/presentation/view_properties/) | Haalt de weergave-eigenschappen voor de hele presentatie op.<br/>            Alleen-lezen [`IViewProperties`](/slides/python-net/nl/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/nl/aspose.slides/presentation/first_slide_number/) | Stelt het eerste dia-nummer in de presentatie voor |
| [`sensitivity_labels`](/slides/python-net/nl/aspose.slides/presentation/sensitivity_labels/) | Geeft de verzameling van gevoeligheidslabels die op het presentatiedocument zijn toegepast terug.<br/>            Alleen-lezen [`ISensitivityLabelCollection`](/slides/python-net/nl/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/nl/aspose.slides/presentation/source_format/) | Geeft informatie over het formaat waarin de presentatie is geladen terug.<br/>            Alleen-lezen [`SourceFormat`](/slides/python-net/nl/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/nl/aspose.slides/presentation/master_theme/) | Geeft het master-thema terug.<br/>            Alleen-lezen [`IMasterTheme`](/slides/python-net/nl/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/nl/aspose.slides/presentation/presentation/) |  |

## Methoden

| Methode | Omschrijving |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/nl/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [`save(self, stream, format)`](/slides/python-net/nl/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat. |
| [`save(self, fname, format, options)`](/slides/python-net/nl/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/nl/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat en met extra opties. |
| [`save(self, options)`](/slides/python-net/nl/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Slaat alle dia's van een presentatie op in een reeks bestanden die XAML-markering weergeven. |
| [`save(self, fname, slides, format)`](/slides/python-net/nl/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat, met behoud van paginanummer. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/nl/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat, met behoud van paginanummer. |
| [`save(self, stream, slides, format)`](/slides/python-net/nl/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat, met behoud van paginanummer. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/nl/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat, met behoud van paginanummer. |
| [`get_images(self, options)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Geeft Image-objecten terug voor alle dia's van een presentatie. |
| [`get_images(self, options, slides)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Geeft Thumbnail-Image-objecten terug voor opgegeven dia's van een presentatie. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Geeft Thumbnail-Image-objecten terug voor alle dia's van een presentatie met aangepaste schaal. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Geeft Thumbnail-Image-objecten terug voor opgegeven dia's van een presentatie met aangepaste schaal. |
| [`get_images(self, options, image_size)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Geeft Thumbnail-Image-objecten terug voor alle dia's van een presentatie met opgegeven grootte. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/nl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Geeft Thumbnail-Image-objecten terug voor opgegeven dia's van een presentatie met opgegeven grootte. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/nl/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/nl/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [`get_slide_by_id(self, id)`](/slides/python-net/nl/aspose.slides/presentation/get_slide_by_id/#int) | Geeft een Slide, MasterSlide of LayoutSlide terug op Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/presentation/join_portions_with_same_formatting/#) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle geschikte vormen in alle dia's. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/nl/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/nl/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/nl/aspose.slides/presentation/replace_regex/#str-str) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)