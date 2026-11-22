---
title: Presentation class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/presentation/
---
## Presentationklass

Representerar en Microsoft PowerPoint-presentation.

Presentation-typen exponeras följande medlemmar:

## Konstruktörer

| Konstruktör | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#) | Denna konstruktor skapar en ny presentation från grunden.<br/>            Skapad presentation har en tom bild. |
| [`__init__(self, load_options)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#loadoptions) | Denna konstruktor skapar en ny presentation från grunden.<br/>            Skapad presentation har en tom bild. |
| [`__init__(self, stream)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#iorawiobase) | Denna konstruktor är den primära mekanismen för att läsa en befintlig Presentation. |
| [`__init__(self, stream, load_options)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Denna konstruktor är den primära mekanismen för att läsa en befintlig Presentation. |
| [`__init__(self, file)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#str) | Denna konstruktor får en källfilssökväg från vilken<br/>             innehållet i Presentationen läses. |
| [`__init__(self, file, load_options)`](/slides/python-net/sv/aspose.slides/presentation/__init__/#str-loadoptions) | Denna konstruktor får en källfilssökväg från vilken<br/>            innehållet i Presentationen läses. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`current_date_time`](/slides/python-net/sv/aspose.slides/presentation/current_date_time/) | Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält.<br/>            Tid för skapandet av detta Presentation-objekt som standard.<br/>            Läs/skriv **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/sv/aspose.slides/presentation/header_footer_manager/) | Returnerar aktuell HeaderFooter-hanterare.<br/>            Endast läsning [`IPresentationHeaderFooterManager`](/slides/python-net/sv/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/sv/aspose.slides/presentation/protection_manager/) | Hämtar hanterare för behörigheter för denna presentation.<br/>            Endast läsning [`IProtectionManager`](/slides/python-net/sv/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/sv/aspose.slides/presentation/slides/) | Returnerar en lista över alla bilder som är definierade i presentationen.<br/sv/>            Endast läsning [`ISlideCollection`](/slides/python-net/sv/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/sv/aspose.slides/presentation/sections/) | Returnerar en lista över alla bildsektioner som är definierade i presentationen.<br/>            Endast läsning [`ISectionCollection`](/slides/python-net/sv/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/sv/aspose.slides/presentation/slide_size/) | Returnerar bildstorleksobjekt.<br/>            Endast läsning [`ISlideSize`](/slides/python-net/sv/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/sv/aspose.slides/presentation/notes_size/) | Returnerar objekt för noteringsbildstorlek.<br/>            Endast läsning [`INotesSize`](/slides/python-net/sv/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/sv/aspose.slides/presentation/layout_slides/) | Returnerar en lista över alla layoutbilder som är definierade i presentationen.<br/>            Endast läsning [`IGlobalLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/sv/aspose.slides/presentation/masters/) | Returnerar en lista över alla mastrebilder som är definierade i presentationen.<br/>            Endast läsning [`IMasterSlideCollection`](/slides/python-net/sv/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/sv/aspose.slides/presentation/master_notes_slide_manager/) | Returnerar notermasterhanterare.<br/>            Endast läsning [`IMasterNotesSlideManager`](/slides/python-net/sv/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/sv/aspose.slides/presentation/master_handout_slide_manager/) | Returnerar utdelningsmasterhanterare.<br/>            Endast läsning [`IMasterHandoutSlideManager`](/slides/python-net/sv/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/sv/aspose.slides/presentation/fonts_manager/) | Returnerar typsnittshanterare.<br/>            Endast läsning [`IFontsManager`](/slides/python-net/sv/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/sv/aspose.slides/presentation/default_text_style/) | Returnerar standardtextstil för former.<br/>            Endast läsning [`ITextStyle`](/slides/python-net/sv/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/sv/aspose.slides/presentation/comment_authors/) | Returnerar samlingen av kommentarer-författare.<br/>            Endast läsning [`ICommentAuthorCollection`](/slides/python-net/sv/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/sv/aspose.slides/presentation/document_properties/) | Returnerar DocumentProperties-objekt som innehåller standard- och anpassade dokumentegenskaper.<br/>            Endast läsning [`IDocumentProperties`](/slides/python-net/sv/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/sv/aspose.slides/presentation/images/) | Returnerar samlingen av alla bilder i presentationen.<br/>            Endast läsning [`IImageCollection`](/slides/python-net/sv/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/sv/aspose.slides/presentation/audios/) | Returnerar samlingen av alla inbäddade ljudfiler i presentationen.<br/>            Endast läsning [`IAudioCollection`](/slides/python-net/sv/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/sv/aspose.slides/presentation/videos/) | Returnerar samlingen av alla inbäddade videofiler i presentationen.<br/>            Endast läsning [`IVideoCollection`](/slides/python-net/sv/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/sv/aspose.slides/presentation/slide_show_settings/) | Returnerar bildspelsinställningarna för presentationen. |
| [`digital_signatures`](/slides/python-net/sv/aspose.slides/presentation/digital_signatures/) | Returnerar samlingen av signaturer som används för att signera presentationen.<br/>            Endast läsning [`IDigitalSignatureCollection`](/slides/python-net/sv/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/presentation/custom_data/) | Returnerar presentationens anpassade data.<br/>            Endast läsning [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/sv/aspose.slides/presentation/all_custom_xml_parts/) | Returnerar alla anpassade datapartiklar i presentationen.<br/>            Endast läsning [`ICustomXmlPart`](/slides/python-net/sv/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/sv/aspose.slides/presentation/vba_project/) | Hämtar eller anger VBA-projekt med presentationsmakron.<br/>            Läs/skriv [`IVbaProject`](/slides/python-net/sv/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/presentation/hyperlink_queries/) | Ger enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (ej i master-, layout- eller noteringsbilder).<br/>            Endast läsning [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/sv/aspose.slides/presentation/view_properties/) | Hämtar egenskaper för presentationsövergripande vy.<br/>            Endast läsning [`IViewProperties`](/slides/python-net/sv/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/sv/aspose.slides/presentation/first_slide_number/) | Representerar det första bildnumret i presentationen |
| [`sensitivity_labels`](/slides/python-net/sv/aspose.slides/presentation/sensitivity_labels/) | Returnerar samlingen av känslighetsetiketter som tillämpas på presentationsdokumentet.<br/>            Endast läsning [`ISensitivityLabelCollection`](/slides/python-net/sv/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/sv/aspose.slides/presentation/source_format/) | Returnerar information om från vilket format presentationen laddades.<br/>            Endast läsning [`SourceFormat`](/slides/python-net/sv/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/sv/aspose.slides/presentation/master_theme/) | Returnerar mastertema.<br/>            Endast läsning [`IMasterTheme`](/slides/python-net/sv/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/sv/aspose.slides/presentation/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/sv/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Sparar alla bilder i en presentation till en fil med angivet format. |
| [`save(self, stream, format)`](/slides/python-net/sv/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Sparar alla bilder i en presentation till en ström i angivet format. |
| [`save(self, fname, format, options)`](/slides/python-net/sv/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/sv/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Sparar alla bilder i en presentation till en ström i angivet format och med ytterligare alternativ. |
| [`save(self, options)`](/slides/python-net/sv/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup. |
| [`save(self, fname, slides, format)`](/slides/python-net/sv/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Sparar angivna bilder i en presentation till en fil med angivet format med bibehållen sidnummer. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/sv/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Sparar angivna bilder i en presentation till en fil med angivet format med bibehållen sidnummer. |
| [`save(self, stream, slides, format)`](/slides/python-net/sv/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Sparar angivna bilder i en presentation till en ström i angivet format med bibehållen sidnummer. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/sv/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Sparar angivna bilder i en presentation till en ström i angivet format med bibehållen sidnummer. |
| [`get_images(self, options)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Returnerar Image-objekt för alla bilder i en presentation. |
| [`get_images(self, options, slides)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Returnerar Thumbnail-Image-objekt för angivna bilder i en presentation. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Returnerar Thumbnail-Image-objekt för alla bilder i en presentation med anpassad skalning. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Returnerar Thumbnail-Image-objekt för angivna bilder i en presentation med anpassad skalning. |
| [`get_images(self, options, image_size)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Returnerar Thumbnail-Image-objekt för alla bilder i en presentation med specificerad storlek. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/sv/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Returnerar Thumbnail-Image-objekt för angivna bilder i en presentation med specificerad storlek. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/sv/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Markerar alla förekomster av exempeltexten med den angivna färgen. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/sv/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Markerar alla förekomster av exempeltexten med den angivna färgen. |
| [`get_slide_by_id(self, id)`](/slides/python-net/sv/aspose.slides/presentation/get_slide_by_id/#int) | Returnerar en Slide, MasterSlide eller LayoutSlide med Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/presentation/join_portions_with_same_formatting/#) | Slår ihop körningar med samma formatering i alla stycken i alla godkända former i alla bilder. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/sv/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Markerar alla förekomster av reguljära uttrycket med den angivna färgen. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/sv/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/sv/aspose.slides/presentation/replace_regex/#str-str) | Ersätter alla matchningar av reguljära uttrycket med den angivna strängen. |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/sv/aspose.slides/presentation/refresh_charts_data/#bool) | Laddar om data för alla diagram i presentationen från deras källarbok. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)