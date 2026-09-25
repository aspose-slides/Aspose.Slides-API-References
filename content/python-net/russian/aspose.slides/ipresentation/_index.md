---
title: IPresentation class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ipresentation/
---
## Класс IPresentation

Документ презентации

Тип IPresentation раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/ru/aspose.slides/ipresentation/current_date_time/) | Returns or sets date and time which will substitute content of datetime fields.<br/>            Time of this Presentation object creation by default.<br/>            Чтение/запись **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/ipresentation/header_footer_manager/) | Returns HeaderFooter manager of the presentation.<br/>            Только для чтения [`IPresentationHeaderFooterManager`](/slides/python-net/ru/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ru/aspose.slides/ipresentation/protection_manager/) | Gets manager of the permissions for this presentation. <br/>            Только для чтения [`IProtectionManager`](/slides/python-net/ru/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ru/aspose.slides/ipresentation/slides/) | Returns a list of all slides that are defined in the presentation.<br/ru/>            Только для чтения [`ISlideCollection`](/slides/python-net/ru/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ru/aspose.slides/ipresentation/sections/) | Returns a list of all slides sections that are defined in the presentation.<br/>            Только для чтения [`ISectionCollection`](/slides/python-net/ru/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ru/aspose.slides/ipresentation/slide_size/) | Returns slide size object.<br/>            Только для чтения [`ISlideSize`](/slides/python-net/ru/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ru/aspose.slides/ipresentation/notes_size/) | Returns notes slide size object.<br/>            Только для чтения [`INotesSize`](/slides/python-net/ru/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ru/aspose.slides/ipresentation/layout_slides/) | Returns a list of all layout slides that are defined in the presentation.<br/>            Только для чтения [`IGlobalLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ru/aspose.slides/ipresentation/masters/) | Returns a list of all master slides that are defined in the presentation.<br/>            Только для чтения [`IMasterSlideCollection`](/slides/python-net/ru/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ru/aspose.slides/ipresentation/master_notes_slide_manager/) | Returns notes master manager.<br/>            Только для чтения [`IMasterNotesSlideManager`](/slides/python-net/ru/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ru/aspose.slides/ipresentation/master_handout_slide_manager/) | Returns handout master manager.<br/>            Только для чтения [`IMasterHandoutSlideManager`](/slides/python-net/ru/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ru/aspose.slides/ipresentation/fonts_manager/) | Returns fonts manager.<br/>            Только для чтения [`IFontsManager`](/slides/python-net/ru/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ru/aspose.slides/ipresentation/default_text_style/) | Returns default text style for shapes.<br/>            Только для чтения [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ru/aspose.slides/ipresentation/comment_authors/) | Returns the collection of comments autors.<br/>            Только для чтения [`ICommentAuthorCollection`](/slides/python-net/ru/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ru/aspose.slides/ipresentation/document_properties/) | Returns DocumentProperties object which contains standard and custom document properties.<br/>            Только для чтения [`IDocumentProperties`](/slides/python-net/ru/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ru/aspose.slides/ipresentation/images/) | Returns the collection of all images in the presentation.<br/>            Только для чтения [`IImageCollection`](/slides/python-net/ru/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ru/aspose.slides/ipresentation/audios/) | Returns the collection of all embedded audio files in the presentation.<br/>            Только для чтения [`IAudioCollection`](/slides/python-net/ru/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ru/aspose.slides/ipresentation/videos/) | Returns the collection of all embedded video files in the presentation.<br/>            Только для чтения [`IVideoCollection`](/slides/python-net/ru/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/ipresentation/custom_data/) | Returns the presentation's custom data.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/ru/aspose.slides/ipresentation/vba_project/) | Gets VBA project with presentation macros.<br/>            Чтение/запись [`IVbaProject`](/slides/python-net/ru/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/ru/aspose.slides/ipresentation/source_format/) | Returns information about from which format presentation was loaded.<br/>            Только для чтения [`IPresentation.source_format`](/slides/python-net/ru/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/ru/aspose.slides/ipresentation/master_theme/) | Returns master theme of the presentation.<br/>            Только для чтения [`IMasterTheme`](/slides/python-net/ru/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/ipresentation/hyperlink_queries/) | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides).<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ru/aspose.slides/ipresentation/view_properties/) | Gets presentation wide view properties.<br/>            Только для чтения [`IViewProperties`](/slides/python-net/ru/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ru/aspose.slides/ipresentation/first_slide_number/) | Represents the first slide number in the presentation.<br/>            Чтение/запись **int**. |
| [`all_custom_xml_parts`](/slides/python-net/ru/aspose.slides/ipresentation/all_custom_xml_parts/) | Returns all custom data parts in the presentaion.<br/>            Только для чтения [`ICustomXmlPart`](/slides/python-net/ru/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/ru/aspose.slides/ipresentation/digital_signatures/) | Returns the collection of signatures used to sign the presentation.<br/>            Только для чтения [`IDigitalSignatureCollection`](/slides/python-net/ru/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/ru/aspose.slides/ipresentation/sensitivity_labels/) | Returns the collection of sensitivity labels applied to the presentation document.<br/>            Только для чтения [`ISensitivityLabelCollection`](/slides/python-net/ru/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/ru/aspose.slides/ipresentation/presentation/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ru/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | Saves all slides of a presentation to a file with the specified format. |
| [`save(self, stream, format)`](/slides/python-net/ru/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | Saves all slides of a presentation to a stream in the specified format. |
| [`save(self, fname, format, options)`](/slides/python-net/ru/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [`save(self, stream, format, options)`](/slides/python-net/ru/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [`save(self, fname, slides, format)`](/slides/python-net/ru/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | Saves specified slides of a presentation to a file with the specified format. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ru/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves specified slides of a presentation to a file with the specified format. |
| [`save(self, stream, slides, format)`](/slides/python-net/ru/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Saves specified slides of a presentation to a stream in the specified format. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ru/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves specified slides of a presentation to a stream in the specified format. |
| [`save(self, options)`](/slides/python-net/ru/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [`get_images(self, options)`](/slides/python-net/ru/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Image objects for all slides of a presentation. |
| [`get_images(self, options, slides)`](/slides/python-net/ru/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Image objects for all slides of a presentation with custom scaling. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling. |
| [`get_images(self, options, image_size)`](/slides/python-net/ru/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Returns a Thumbnail Image objects for all slides of a presentation with specified size. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ru/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Returns a Thumbnail Image objects for specified slides of a presentation with specified size. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ru/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ru/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Highlights all matches of the sample text with the specified color. |
| [`get_slide_by_id(self, id)`](/slides/python-net/ru/aspose.slides/ipresentation/get_slide_by_id/#int) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ru/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | Highlights all matches of the regular expression with the specified color. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ru/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Replaces all occurrences of the specified text with another specified text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ru/aspose.slides/ipresentation/replace_regex/#str-str) | Replaces all matches of the regular expression with the specified string. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)