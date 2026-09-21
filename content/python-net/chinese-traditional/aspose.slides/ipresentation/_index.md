---
title: IPresentation class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ipresentation/
---
## IPresentation 類別

Presentation 文件

IPresentation 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`current_date_time`](/slides/python-net/zh-hant/aspose.slides/ipresentation/current_date_time/) | Returns or sets date and time which will substitute content of datetime fields.<br/>            Time of this Presentation object creation by default.<br/>            讀/寫 **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/ipresentation/header_footer_manager/) | Returns HeaderFooter manager of the presentation.<br/>            唯讀 [`IPresentationHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/zh-hant/aspose.slides/ipresentation/protection_manager/) | Gets manager of the permissions for this presentation. <br/>            唯讀 [`IProtectionManager`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/zh-hant/aspose.slides/ipresentation/slides/) | Returns a list of all slides that are defined in the presentation.<br/zh-hant/>            唯讀 [`ISlideCollection`](/slides/python-net/zh-hant/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/zh-hant/aspose.slides/ipresentation/sections/) | Returns a list of all slides sections that are defined in the presentation.<br/>            唯讀 [`ISectionCollection`](/slides/python-net/zh-hant/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/zh-hant/aspose.slides/ipresentation/slide_size/) | Returns slide size object.<br/>            唯讀 [`ISlideSize`](/slides/python-net/zh-hant/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/zh-hant/aspose.slides/ipresentation/notes_size/) | Returns notes slide size object.<br/>            唯讀 [`INotesSize`](/slides/python-net/zh-hant/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/zh-hant/aspose.slides/ipresentation/layout_slides/) | Returns a list of all layout slides that are defined in the presentation.<br/>            唯讀 [`IGlobalLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/zh-hant/aspose.slides/ipresentation/masters/) | Returns a list of all master slides that are defined in the presentation.<br/>            唯讀 [`IMasterSlideCollection`](/slides/python-net/zh-hant/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/zh-hant/aspose.slides/ipresentation/master_notes_slide_manager/) | Returns notes master manager.<br/>            唯讀 [`IMasterNotesSlideManager`](/slides/python-net/zh-hant/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/zh-hant/aspose.slides/ipresentation/master_handout_slide_manager/) | Returns handout master manager.<br/>            唯讀 [`IMasterHandoutSlideManager`](/slides/python-net/zh-hant/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/zh-hant/aspose.slides/ipresentation/fonts_manager/) | Returns fonts manager.<br/>            唯讀 [`IFontsManager`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/zh-hant/aspose.slides/ipresentation/default_text_style/) | Returns default text style for shapes.<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/zh-hant/aspose.slides/ipresentation/comment_authors/) | Returns the collection of comments autors.<br/>            唯讀 [`ICommentAuthorCollection`](/slides/python-net/zh-hant/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/zh-hant/aspose.slides/ipresentation/document_properties/) | Returns DocumentProperties object which contains standard and custom document properties.<br/>            唯讀 [`IDocumentProperties`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/zh-hant/aspose.slides/ipresentation/images/) | Returns the collection of all images in the presentation.<br/>            唯讀 [`IImageCollection`](/slides/python-net/zh-hant/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/zh-hant/aspose.slides/ipresentation/audios/) | Returns the collection of all embedded audio files in the presentation.<br/>            唯讀 [`IAudioCollection`](/slides/python-net/zh-hant/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/zh-hant/aspose.slides/ipresentation/videos/) | Returns the collection of all embedded video files in the presentation.<br/>            唯讀 [`IVideoCollection`](/slides/python-net/zh-hant/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/ipresentation/custom_data/) | Returns the presentation's custom data.<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/zh-hant/aspose.slides/ipresentation/vba_project/) | Gets VBA project with presentation macros.<br/>            讀/寫 [`IVbaProject`](/slides/python-net/zh-hant/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/zh-hant/aspose.slides/ipresentation/source_format/) | Returns information about from which format presentation was loaded.<br/>            唯讀 [`IPresentation.source_format`](/slides/python-net/zh-hant/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/zh-hant/aspose.slides/ipresentation/master_theme/) | Returns master theme of the presentation.<br/>            唯讀 [`IMasterTheme`](/slides/python-net/zh-hant/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/ipresentation/hyperlink_queries/) | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides).<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/zh-hant/aspose.slides/ipresentation/view_properties/) | Gets presentation wide view properties.<br/>            唯讀 [`IViewProperties`](/slides/python-net/zh-hant/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/zh-hant/aspose.slides/ipresentation/first_slide_number/) | Represents the first slide number in the presentation.<br/>            讀/寫 **int**. |
| [`all_custom_xml_parts`](/slides/python-net/zh-hant/aspose.slides/ipresentation/all_custom_xml_parts/) | Returns all custom data parts in the presentaion.<br/>            唯讀 [`ICustomXmlPart`](/slides/python-net/zh-hant/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/zh-hant/aspose.slides/ipresentation/digital_signatures/) | Returns the collection of signatures used to sign the presentation.<br/>            唯讀 [`IDigitalSignatureCollection`](/slides/python-net/zh-hant/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/zh-hant/aspose.slides/ipresentation/sensitivity_labels/) | Returns the collection of sensitivity labels applied to the presentation document.<br/>            唯讀 [`ISensitivityLabelCollection`](/slides/python-net/zh-hant/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation/presentation/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | Saves all slides of a presentation to a file with the specified format. |
| [`save(self, stream, format)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | Saves all slides of a presentation to a stream in the specified format. |
| [`save(self, fname, format, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [`save(self, stream, format, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [`save(self, fname, slides, format)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | Saves specified slides of a presentation to a file with the specified format. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves specified slides of a presentation to a file with the specified format. |
| [`save(self, stream, slides, format)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Saves specified slides of a presentation to a stream in the specified format. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Saves specified slides of a presentation to a stream in the specified format. |
| [`save(self, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [`get_images(self, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Image objects for all slides of a presentation. |
| [`get_images(self, options, slides)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Image objects for all slides of a presentation with custom scaling. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling. |
| [`get_images(self, options, image_size)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Returns a Thumbnail Image objects for all slides of a presentation with specified size. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Returns a Thumbnail Image objects for specified slides of a presentation with specified size. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/highlight_text/#str-asposepydrawingcolor) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Highlights all matches of the sample text with the specified color. |
| [`get_slide_by_id(self, id)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_slide_by_id/#int) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/highlight_regex/#str-asposepydrawingcolor) | Highlights all matches of the regular expression with the specified color. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Replaces all occurrences of the specified text with another specified text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/replace_regex/#str-str) | Replaces all matches of the regular expression with the specified string. |

### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)