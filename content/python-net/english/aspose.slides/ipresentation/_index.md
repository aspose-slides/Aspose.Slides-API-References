---
title: IPresentation class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ipresentation/
---


## IPresentation class

Presentation document

The IPresentation type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/aspose.slides/ipresentation/current_date_time/) | Returns or sets date and time which will substitute content of datetime fields.<br/>            Time of this Presentation object creation by default.<br/>            Read/write **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/aspose.slides/ipresentation/header_footer_manager/) | Returns HeaderFooter manager of the presentation.<br/>            Read-only [`IPresentationHeaderFooterManager`](/slides/python-net/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/aspose.slides/ipresentation/protection_manager/) | Gets manager of the permissions for this presentation. <br/>            Read-only [`IProtectionManager`](/slides/python-net/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/aspose.slides/ipresentation/slides/) | Returns a list of all slides that are defined in the presentation.<br/>            Read-only [`ISlideCollection`](/slides/python-net/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/aspose.slides/ipresentation/sections/) | Returns a list of all slides sections that are defined in the presentation.<br/>            Read-only [`ISectionCollection`](/slides/python-net/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/aspose.slides/ipresentation/slide_size/) | Returns slide size object.<br/>            Read-only [`ISlideSize`](/slides/python-net/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/aspose.slides/ipresentation/notes_size/) | Returns notes slide size object.<br/>            Read-only [`INotesSize`](/slides/python-net/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/aspose.slides/ipresentation/layout_slides/) | Returns a list of all layout slides that are defined in the presentation.<br/>            Read-only [`IGlobalLayoutSlideCollection`](/slides/python-net/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/aspose.slides/ipresentation/masters/) | Returns a list of all master slides that are defined in the presentation.<br/>            Read-only [`IMasterSlideCollection`](/slides/python-net/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/aspose.slides/ipresentation/master_notes_slide_manager/) | Returns notes master manager.<br/>            Read-only [`IMasterNotesSlideManager`](/slides/python-net/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/aspose.slides/ipresentation/master_handout_slide_manager/) | Returns handout master manager.<br/>            Read-only [`IMasterHandoutSlideManager`](/slides/python-net/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/aspose.slides/ipresentation/fonts_manager/) | Returns fonts manager.<br/>            Read-only [`IFontsManager`](/slides/python-net/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/aspose.slides/ipresentation/default_text_style/) | Returns default text style for shapes.<br/>            Read-only [`ITextStyle`](/slides/python-net/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/aspose.slides/ipresentation/comment_authors/) | Returns the collection of comments autors.<br/>            Read-only [`ICommentAuthorCollection`](/slides/python-net/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/aspose.slides/ipresentation/document_properties/) | Returns DocumentProperties object which contains standard and custom document properties.<br/>            Read-only [`IDocumentProperties`](/slides/python-net/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/aspose.slides/ipresentation/images/) | Returns the collection of all images in the presentation.<br/>            Read-only [`IImageCollection`](/slides/python-net/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/aspose.slides/ipresentation/audios/) | Returns the collection of all embedded audio files in the presentation.<br/>            Read-only [`IAudioCollection`](/slides/python-net/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/aspose.slides/ipresentation/videos/) | Returns the collection of all embedded video files in the presentation.<br/>            Read-only [`IVideoCollection`](/slides/python-net/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/aspose.slides/ipresentation/custom_data/) | Returns the presentation's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/aspose.slides/ipresentation/vba_project/) | Gets VBA project with presentation macros.<br/>            Read/write [`IVbaProject`](/slides/python-net/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/aspose.slides/ipresentation/source_format/) | Returns information about from which format presentation was loaded.<br/>            Read-only [`IPresentation.source_format`](/slides/python-net/aspose.slides/ipresentation#source_format). |
| [`master_theme`](/slides/python-net/aspose.slides/ipresentation/master_theme/) | Returns master theme of the presentation.<br/>            Read-only [`IMasterTheme`](/slides/python-net/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/aspose.slides/ipresentation/hyperlink_queries/) | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides).<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/aspose.slides/ipresentation/view_properties/) | Gets presentation wide view properties.<br/>            Read-only [`IViewProperties`](/slides/python-net/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/aspose.slides/ipresentation/first_slide_number/) | Represents the first slide number in the presentation.<br/>            Read/write **int**. |
| [`all_custom_xml_parts`](/slides/python-net/aspose.slides/ipresentation/all_custom_xml_parts/) | Returns all custom data parts in the presentaion.<br/>            Read-only [`ICustomXmlPart`](/slides/python-net/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/aspose.slides/ipresentation/digital_signatures/) | Returns the collection of signatures used to sign the presentation.<br/>            Read-only [`IDigitalSignatureCollection`](/slides/python-net/aspose.slides/idigitalsignaturecollection). |
| [`presentation`](/slides/python-net/aspose.slides/ipresentation/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`save`](/slides/python-net/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | Saves all slides of a presentation to a file with the specified format. |
| [`save`](/slides/python-net/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | Saves all slides of a presentation to a stream in the specified format. |
| [`save`](/slides/python-net/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [`save`](/slides/python-net/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [`save`](/slides/python-net/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | Saves specified slides of a presentation to a file with the specified format. |
| [`save`](/slides/python-net/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves specified slides of a presentation to a file with the specified format. |
| [`save`](/slides/python-net/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Saves specified slides of a presentation to a stream in the specified format. |
| [`save`](/slides/python-net/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves specified slides of a presentation to a stream in the specified format. |
| [`save`](/slides/python-net/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [`get_thumbnails`](/slides/python-net/aspose.slides/ipresentation/get_thumbnails/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Bitmap objects for all slides of a presentation. |
| [`get_thumbnails`](/slides/python-net/aspose.slides/ipresentation/get_thumbnails/#asposeslidesexportirenderingoptions-listint) | Returns a Thumbnail Image objects for specified slides of a presentation. |
| [`get_thumbnails`](/slides/python-net/aspose.slides/ipresentation/get_thumbnails/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling. |
| [`get_thumbnails`](/slides/python-net/aspose.slides/ipresentation/get_thumbnails/#asposeslidesexportirenderingoptions-listint-float-float) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling. |
| [`get_thumbnails`](/slides/python-net/aspose.slides/ipresentation/get_thumbnails/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size. |
| [`get_thumbnails`](/slides/python-net/aspose.slides/ipresentation/get_thumbnails/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| [`get_images`](/slides/python-net/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Image objects for all slides of a presentation. |
| [`get_images`](/slides/python-net/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [`get_images`](/slides/python-net/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Image objects for all slides of a presentation with custom scaling. |
| [`get_images`](/slides/python-net/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling. |
| [`get_images`](/slides/python-net/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Returns a Thumbnail Image objects for all slides of a presentation with specified size. |
| [`get_images`](/slides/python-net/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Returns a Thumbnail Image objects for specified slides of a presentation with specified size. |
| [`print`](/slides/python-net/aspose.slides/ipresentation/print/#) | Prints the whole presentation to the default printer. |
| [`print`](/slides/python-net/aspose.slides/ipresentation/print/#asposepydrawingprintingprintersettings) | Prints the presentation according to the specified printer settings,<br/>            using the standard (no User Interface) print controller. |
| [`print`](/slides/python-net/aspose.slides/ipresentation/print/#str) | Print the whole presentation to the specified printer,<br/>            using the standard (no User Interface) print controller. |
| [`print`](/slides/python-net/aspose.slides/ipresentation/print/#asposepydrawingprintingprintersettings-str) | Prints the document according to the specified printer settings, using<br/>            the standard (no User Interface) print controller and a presentation name. |
| [`highlight_text`](/slides/python-net/aspose.slides/ipresentation/highlight_text/#str-asposepydrawingcolor) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text`](/slides/python-net/aspose.slides/ipresentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Highlights all matches of the sample text with the specified color. |
| [`get_slide_by_id`](/slides/python-net/aspose.slides/ipresentation/get_slide_by_id/#int) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [`join_portions_with_same_formatting`](/slides/python-net/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [`replace_text`](/slides/python-net/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Replaces all occurrences of the specified text with another specified text. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

