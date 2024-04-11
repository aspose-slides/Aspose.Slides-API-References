---
title: Presentation
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/presentation/
---


Presentation class

Represents a Microsoft PowerPoint presentation.

The Presentation type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/presentation/__init__/#) | This constructor creates new presentation from scratch.<br/>            Created presentation has one empty slide. |
| [__init__](/slides/python-net/aspose.slides/presentation/__init__/#LoadOptions) | This constructor creates new presentation from scratch.<br/>            Created presentation has one empty slide. |
| [__init__](/slides/python-net/aspose.slides/presentation/__init__/#System.IO.Stream) | This constructor is the primary mechanism for reading an existing Presentation. |
| [__init__](/slides/python-net/aspose.slides/presentation/__init__/#System.IO.Stream-LoadOptions) | This constructor is the primary mechanism for reading an existing Presentation. |
| [__init__](/slides/python-net/aspose.slides/presentation/__init__/#string) | This constructor gets a source file path from which<br/>             the contents of the Presentation are read. |
| [__init__](/slides/python-net/aspose.slides/presentation/__init__/#string-LoadOptions) | This constructor gets a source file path from which<br/>            the contents of the Presentation are read. |

## Properties

| Property | Description |
| :- | :- |
| [current_date_time](/slides/python-net/aspose.slides/presentation/current_date_time/) | Returns or sets date and time which will substitute content of datetime fields.<br/>            Time of this Presentation object creation by default.<br/>            Read/write .NET type System.DateTime. |
| [header_footer_manager](/slides/python-net/aspose.slides/presentation/header_footer_manager/) | Returns actual HeaderFooter manager.<br/>            Read-only [`IPresentationHeaderFooterManager`](/slides/python-net/aspose.slides/ipresentationheaderfootermanager). |
| [protection_manager](/slides/python-net/aspose.slides/presentation/protection_manager/) | Gets manager of the permissions for this presentation.<br/>            Read-only [`IProtectionManager`](/slides/python-net/aspose.slides/iprotectionmanager). |
| [slides](/slides/python-net/aspose.slides/presentation/slides/) | Returns a list of all slides that are defined in the presentation.<br/>            Read-only [`ISlideCollection`](/slides/python-net/aspose.slides/islidecollection). |
| [sections](/slides/python-net/aspose.slides/presentation/sections/) | Returns a list of all slides sections that are defined in the presentation.<br/>            Read-only [`ISectionCollection`](/slides/python-net/aspose.slides/isectioncollection). |
| [slide_size](/slides/python-net/aspose.slides/presentation/slide_size/) | Returns slide size object.<br/>            Read-only [`ISlideSize`](/slides/python-net/aspose.slides/islidesize). |
| [notes_size](/slides/python-net/aspose.slides/presentation/notes_size/) | Returns notes slide size object.<br/>            Read-only [`INotesSize`](/slides/python-net/aspose.slides/inotessize). |
| [layout_slides](/slides/python-net/aspose.slides/presentation/layout_slides/) | Returns a list of all layout slides that are defined in the presentation.<br/>            Read-only [`IGlobalLayoutSlideCollection`](/slides/python-net/aspose.slides/igloballayoutslidecollection). |
| [masters](/slides/python-net/aspose.slides/presentation/masters/) | Returns a list of all master slides that are defined in the presentation.<br/>            Read-only [`IMasterSlideCollection`](/slides/python-net/aspose.slides/imasterslidecollection). |
| [master_notes_slide_manager](/slides/python-net/aspose.slides/presentation/master_notes_slide_manager/) | Returns notes master manager.<br/>            Read-only [`IMasterNotesSlideManager`](/slides/python-net/aspose.slides/imasternotesslidemanager). |
| [master_handout_slide_manager](/slides/python-net/aspose.slides/presentation/master_handout_slide_manager/) | Returns handout master manager.<br/>            Read-only [`IMasterHandoutSlideManager`](/slides/python-net/aspose.slides/imasterhandoutslidemanager). |
| [fonts_manager](/slides/python-net/aspose.slides/presentation/fonts_manager/) | Returns fonts manager.<br/>            Read-only [`IFontsManager`](/slides/python-net/aspose.slides/ifontsmanager). |
| [default_text_style](/slides/python-net/aspose.slides/presentation/default_text_style/) | Returns default text style for shapes.<br/>            Read-only [`ITextStyle`](/slides/python-net/aspose.slides/itextstyle). |
| [comment_authors](/slides/python-net/aspose.slides/presentation/comment_authors/) | Returns the collection of comments autors.<br/>            Read-only [`ICommentAuthorCollection`](/slides/python-net/aspose.slides/icommentauthorcollection). |
| [document_properties](/slides/python-net/aspose.slides/presentation/document_properties/) | Returns DocumentProperties object which contains standard and custom document properties.<br/>            Read-only [`IDocumentProperties`](/slides/python-net/aspose.slides/idocumentproperties). |
| [images](/slides/python-net/aspose.slides/presentation/images/) | Returns the collection of all images in the presentation.<br/>            Read-only [`IImageCollection`](/slides/python-net/aspose.slides/iimagecollection). |
| [audios](/slides/python-net/aspose.slides/presentation/audios/) | Returns the collection of all embedded audio files in the presentation.<br/>            Read-only [`IAudioCollection`](/slides/python-net/aspose.slides/iaudiocollection). |
| [videos](/slides/python-net/aspose.slides/presentation/videos/) | Returns the collection of all embedded video files in the presentation.<br/>            Read-only [`IVideoCollection`](/slides/python-net/aspose.slides/ivideocollection). |
| [slide_show_settings](/slides/python-net/aspose.slides/presentation/slide_show_settings/) | Returns the slide show settings for the presentation. |
| [digital_signatures](/slides/python-net/aspose.slides/presentation/digital_signatures/) | Returns the collection of signatures used to sign the presentation.<br/>            Read-only [`IDigitalSignatureCollection`](/slides/python-net/aspose.slides/idigitalsignaturecollection). |
| [custom_data](/slides/python-net/aspose.slides/presentation/custom_data/) | Returns the presentation's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [all_custom_xml_parts](/slides/python-net/aspose.slides/presentation/all_custom_xml_parts/) | Returns all custom data parts in the presentaion.<br/>            Read-only [`ICustomXmlPart`](/slides/python-net/aspose.slides/icustomxmlpart)[]. |
| [vba_project](/slides/python-net/aspose.slides/presentation/vba_project/) | Gets or sets VBA project with presentation macros.<br/>            Read/write [`IVbaProject`](/slides/python-net/aspose.slides.vba/ivbaproject). |
| [hyperlink_queries](/slides/python-net/aspose.slides/presentation/hyperlink_queries/) | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides).<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/aspose.slides/ihyperlinkqueries). |
| [view_properties](/slides/python-net/aspose.slides/presentation/view_properties/) | Gets presentation wide view properties.<br/>            Read-only [`IViewProperties`](/slides/python-net/aspose.slides/iviewproperties). |
| [first_slide_number](/slides/python-net/aspose.slides/presentation/first_slide_number/) | Represents the first slide number in the presentation |
| [source_format](/slides/python-net/aspose.slides/presentation/source_format/) | Returns information about from which format presentation was loaded.<br/>            Read-only [`SourceFormat`](/slides/python-net/aspose.slides/sourceformat). |
| [master_theme](/slides/python-net/aspose.slides/presentation/master_theme/) | Returns master theme.<br/>            Read-only [`IMasterTheme`](/slides/python-net/aspose.slides.theme/imastertheme). |
| [as_i_disposable](/slides/python-net/aspose.slides/presentation/as_i_disposable/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/presentation/as_i_presentation_component/) |  |
| [presentation](/slides/python-net/aspose.slides/presentation/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [save](/slides/python-net/aspose.slides/presentation/save/#string-aspose.slides.export.SaveFormat) | Saves all slides of a presentation to a file with the specified format. |
| [save](/slides/python-net/aspose.slides/presentation/save/#System.IO.Stream-aspose.slides.export.SaveFormat) | Saves all slides of a presentation to a stream in the specified format. |
| [save](/slides/python-net/aspose.slides/presentation/save/#string-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions) |  |
| [save](/slides/python-net/aspose.slides/presentation/save/#System.IO.Stream-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](/slides/python-net/aspose.slides/presentation/save/#aspose.slides.export.xaml.IXamlOptions) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [save](/slides/python-net/aspose.slides/presentation/save/#string-List[int]-aspose.slides.export.SaveFormat) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](/slides/python-net/aspose.slides/presentation/save/#string-List[int]-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](/slides/python-net/aspose.slides/presentation/save/#System.IO.Stream-List[int]-aspose.slides.export.SaveFormat) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](/slides/python-net/aspose.slides/presentation/save/#System.IO.Stream-List[int]-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.INotesCommentsLayoutingOptions) | Returns a Thumbnail Bitmap objects for all slides of a presentation. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.INotesCommentsLayoutingOptions-List[int]) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.INotesCommentsLayoutingOptions-float-float) | Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.INotesCommentsLayoutingOptions-List[int]-float-float) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.INotesCommentsLayoutingOptions-List[int]-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.IRenderingOptions) | Returns a Thumbnail Bitmap objects for all slides of a presentation. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.IRenderingOptions-List[int]) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.IRenderingOptions-float-float) | Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.IRenderingOptions-List[int]-float-float) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size. |
| [get_thumbnails](/slides/python-net/aspose.slides/presentation/get_thumbnails/#aspose.slides.export.IRenderingOptions-List[int]-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| [print](/slides/python-net/aspose.slides/presentation/print/#) | Prints the whole presentation to the default printer. |
| [print](/slides/python-net/aspose.slides/presentation/print/#aspose.pydrawing.Printing.PrinterSettings) | Prints the presentation according to the specified printer settings,<br/>            using the standard (no User Interface) print controller. |
| [print](/slides/python-net/aspose.slides/presentation/print/#string) | Print the whole presentation to the specified printer,<br/>            using the standard (no User Interface) print controller. |
| [print](/slides/python-net/aspose.slides/presentation/print/#aspose.pydrawing.Printing.PrinterSettings-string) | Prints the document according to the specified printer settings, using<br/>            the standard (no User Interface) print controller and a presentation name. |
| [get_slide_by_id](/slides/python-net/aspose.slides/presentation/get_slide_by_id/#int) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/presentation/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |

