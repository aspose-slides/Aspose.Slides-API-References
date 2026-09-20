---
title: Presentation class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/presentation/
---
## Presentation-klass

Representerar en Microsoft PowerPoint-presentation.

Presentation-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#) | Denna konstruktor skapar en ny presentation från början.<br/>            Den skapade presentationen har en tom bild. |
| [`__init__(self, load_options)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#loadoptions) | Denna konstruktor skapar en ny presentation från början.<br/>            Den skapade presentationen har en tom bild. |
| [`__init__(self, stream)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#iorawiobase) | Denna konstruktor är den primära mekanismen för att läsa en befintlig Presentation. |
| [`__init__(self, stream, load_options)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Denna konstruktor är den primära mekanismen för att läsa en befintlig Presentation. |
| [`__init__(self, file)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#str) | Denna konstruktor hämtar en sökväg till källfilen från vilken<br/>             innehållet i Presentation läses. |
| [`__init__(self, file, load_options)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#str-loadoptions) | Denna konstruktor hämtar en sökväg till källfilen från vilken<br/>            innehållet i Presentation läses. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`current_date_time`](/slides/python-net/sv/aspose.slides/presentation/current_date_time/) | Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält.<br/>            Tid för skapandet av detta Presentation-objekt som standard.<br/>            Läs/skriv **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/sv/aspose.slides/presentation/header_footer_manager/) | Returnerar den aktuella HeaderFooter-hanteraren.<br/>            Skrivskyddad [`IPresentationHeaderFooterManager`](/slides/python-net/sv/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/sv/aspose.slides/presentation/protection_manager/) | Hämtar hanteraren för behörigheter för denna presentation.<br/>            Skrivskyddad [`IProtectionManager`](/slides/python-net/sv/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/sv/aspose.slides/presentation/slides/) | Returnerar en lista med alla bilder som definieras i presentationen.<br/sv/>            Skrivskyddad [`ISlideCollection`](/slides/python-net/sv/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/sv/aspose.slides/presentation/sections/) | Returnerar en lista med alla bildsektioner som definieras i presentationen.<br/>            Skrivskyddad [`ISectionCollection`](/slides/python-net/sv/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/sv/aspose.slides/presentation/slide_size/) | Returnerar objekt för bildstorlek.<br/>            Skrivskyddad [`ISlideSize`](/slides/python-net/sv/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/sv/aspose.slides/presentation/notes_size/) | Returnerar objekt för anteckningsbildstorlek.<br/>            Skrivskyddad [`INotesSize`](/slides/python-net/sv/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/sv/aspose.slides/presentation/layout_slides/) | Returnerar en lista med alla layoutbilder som definieras i presentationen.<br/>            Skrivskyddad [`IGlobalLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/sv/aspose.slides/presentation/masters/) | Returnerar en lista med alla masterbilder som definieras i presentationen.<br/>            Skrivskyddad [`IMasterSlideCollection`](/slides/python-net/sv/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/sv/aspose.slides/presentation/master_notes_slide_manager/) | Returnerar hanteraren för anteckningsmaster.<br/>            Skrivskyddad [`IMasterNotesSlideManager`](/slides/python-net/sv/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/sv/aspose.slides/presentation/master_handout_slide_manager/) | Returnerar hanteraren för handout-master.<br/>            Skrivskyddad [`IMasterHandoutSlideManager`](/slides/python-net/sv/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/sv/aspose.slides/presentation/fonts_manager/) | Returnerar teckensnittshanteraren.<br/>            Skrivskyddad [`IFontsManager`](/slides/python-net/sv/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/sv/aspose.slides/presentation/default_text_style/) | Returnerar standardtextstil för former.<br/>            Skrivskyddad [`ITextStyle`](/slides/python-net/sv/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/sv/aspose.slides/presentation/comment_authors/) | Returnerar samlingen av kommentarsförfattare.<br/>            Skrivskyddad [`ICommentAuthorCollection`](/slides/python-net/sv/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/sv/aspose.slides/presentation/document_properties/) | Returnerar DocumentProperties-objekt som innehåller standard- och anpassade dokumentegenskaper.<br/>            Skrivskyddad [`IDocumentProperties`](/slides/python-net/sv/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/sv/aspose.slides/presentation/images/) | Returnerar samlingen av alla bilder i presentationen.<br/>            Skrivskyddad [`IImageCollection`](/slides/python-net/sv/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/sv/aspose.slides/presentation/audios/) | Returnerar samlingen av alla inbäddade ljudfiler i presentationen.<br/>            Skrivskyddad [`IAudioCollection`](/slides/python-net/sv/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/sv/aspose.slides/presentation/videos/) | Returnerar samlingen av alla inbäddade videofiler i presentationen.<br/>            Skrivskyddad [`IVideoCollection`](/slides/python-net/sv/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/sv/aspose.slides/presentation/slide_show_settings/) | Returnerar bildspelsinställningarna för presentationen. |
| [`digital_signatures`](/slides/python-net/sv/aspose.slides/presentation/digital_signatures/) | Returnerar samlingen av signaturer som används för att signera presentationen.<br/>            Skrivskyddad [`IDigitalSignatureCollection`](/slides/python-net/sv/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/presentation/custom_data/) | Returnerar presentationens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/sv/aspose.slides/presentation/all_custom_xml_parts/) | Returnerar alla anpassade datadelar i presentationen.<br/>            Skrivskyddad [`ICustomXmlPart`](/slides/python-net/sv/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/sv/aspose.slides/presentation/vba_project/) | Hämtar eller anger VBA-projekt med presentationsmakron.<br/>            Läs/skriv [`IVbaProject`](/slides/python-net/sv/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/presentation/hyperlink_queries/) | Tillhandahåller enkel åtkomst till alla hyperlänkar i alla presentationsbilder (ej i master-, layout- eller anteckningsbilder).<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/sv/aspose.slides/presentation/view_properties/) | Hämtar visningsegenskaper för hela presentationen.<br/>            Skrivskyddad [`IViewProperties`](/slides/python-net/sv/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/sv/aspose.slides/presentation/first_slide_number/) | Representerar det första bildnumret i presentationen |
| [`sensitivity_labels`](/slides/python-net/sv/aspose.slides/presentation/sensitivity_labels/) | Returnerar samlingen av känslighetsetiketter som tillämpats på presentationsdokumentet.<br/>            Skrivskyddad [`ISensitivityLabelCollection`](/slides/python-net/sv/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/sv/aspose.slides/presentation/source_format/) | Returnerar information om från vilket format presentationen laddades.<br/>            Skrivskyddad [`SourceFormat`](/slides/python-net/sv/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/sv/aspose.slides/presentation/master_theme/) | Returnerar mastertema.<br/>            Skrivskyddad [`IMasterTheme`](/slides/python-net/sv/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/sv/aspose.slides/presentation/presentation/) |   |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/sv/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Sparar alla bilder i en presentation till en fil med det angivna formatet. |
| [`save(self, stream, format)`](/slides/python-net/sv/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Sparar alla bilder i en presentation till en ström i det angivna formatet. |
| [`save(self, fname, format, options)`](/slides/python-net/sv/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |   |
| [`save(self, stream, format, options)`](/slides/python-net/sv/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Sparar alla bilder i en presentation till en ström i det angivna formatet med ytterligare alternativ. |
| [`save(self, options)`](/slides/python-net/sv/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Sparar alla bilder i en presentation till ett set av filer som representerar XAML-markup. |
| [`save(self, fname, slides, format)`](/slides/python-net/sv/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Sparar angivna bilder i en presentation till en fil med det angivna formatet med sidnummer bevarat. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/sv/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Sparar angivna bilder i en presentation till en fil med det angivna formatet med sidnummer bevarat. |
| [`save(self, stream, slides, format)`](/slides/python-net/sv/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Sparar angivna bilder i en presentation till en ström i det angivna formatet med sidnummer bevarat. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/sv/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Sparar angivna bilder i en presentation till en ström i det angivna formatet med sidnummer bevarat. |
| [`get_images(self, options)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Returnerar Image-objekt för alla bilder i en presentation. |
| [`get_images(self, options, slides)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Returnerar miniatyrbild-objekt för angivna bilder i en presentation. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Returnerar miniatyrbild-objekt för alla bilder i en presentation med anpassad skalning. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Returnerar miniatyrbild-objekt för angivna bilder i en presentation med anpassad skalning. |
| [`get_images(self, options, image_size)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Returnerar miniatyrbild-objekt för alla bilder i en presentation med angiven storlek. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Returnerar miniatyrbild-objekt för angivna bilder i en presentation med angiven storlek. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/sv/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/sv/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [`get_slide_by_id(self, id)`](/slides/python-net/sv/aspose.slides/presentation/get_slide_by_id/#int) | Returnerar en Slide, MasterSlide eller LayoutSlide via Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/presentation/join_portions_with_same_formatting/#) | Slår samman körningar med samma formatering i alla stycken i alla godkända former i alla bilder. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/sv/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | Markerar alla matchningar av reguljära uttrycket med den angivna färgen. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/sv/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/sv/aspose.slides/presentation/replace_regex/#str-str) | Ersätter alla matchningar av reguljära uttrycket med den angivna strängen. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)