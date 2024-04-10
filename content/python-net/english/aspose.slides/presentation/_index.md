---
title: Presentation class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## Presentation class

Represents a Microsoft PowerPoint presentation.

The Presentation type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/presentation/#) | This constructor creates new presentation from scratch.<br/>            Created presentation has one empty slide. |
| [__init__](/slides/python-net/aspose.slides/presentation/#LoadOptions) | This constructor creates new presentation from scratch.<br/>            Created presentation has one empty slide. |
| [__init__](/slides/python-net/aspose.slides/presentation/#System.IO.Stream) | This constructor is the primary mechanism for reading an existing Presentation. |
| [__init__](/slides/python-net/aspose.slides/presentation/#System.IO.Stream-LoadOptions) | This constructor is the primary mechanism for reading an existing Presentation. |
| [__init__](/slides/python-net/aspose.slides/presentation/#string) | This constructor gets a source file path from which<br/>             the contents of the Presentation are read. |
| [__init__](/slides/python-net/aspose.slides/presentation/#string-LoadOptions) | This constructor gets a source file path from which<br/>            the contents of the Presentation are read. |

## Properties

| Property | Description |
| :- | :- |
| [current_date_time](/slides/python-net/aspose.slides/current_date_time) | Returns or sets date and time which will substitute content of datetime fields.<br/>            Time of this Presentation object creation by default.<br/>            Read/write :py:class:`System.DateTime`. |
| [header_footer_manager](/slides/python-net/aspose.slides/header_footer_manager) | Returns actual HeaderFooter manager.<br/>            Read-only :py:class:`aspose.slides.IPresentationHeaderFooterManager`. |
| [protection_manager](/slides/python-net/aspose.slides/protection_manager) | Gets manager of the permissions for this presentation.<br/>            Read-only :py:class:`aspose.slides.IProtectionManager`. |
| [slides](/slides/python-net/aspose.slides/slides) | Returns a list of all slides that are defined in the presentation.<br/>            Read-only :py:class:`aspose.slides.ISlideCollection`. |
| [sections](/slides/python-net/aspose.slides/sections) | Returns a list of all slides sections that are defined in the presentation.<br/>            Read-only :py:class:`aspose.slides.ISectionCollection`. |
| [slide_size](/slides/python-net/aspose.slides/slide_size) | Returns slide size object.<br/>            Read-only :py:class:`aspose.slides.ISlideSize`. |
| [notes_size](/slides/python-net/aspose.slides/notes_size) | Returns notes slide size object.<br/>            Read-only :py:class:`aspose.slides.INotesSize`. |
| [layout_slides](/slides/python-net/aspose.slides/layout_slides) | Returns a list of all layout slides that are defined in the presentation.<br/>            Read-only :py:class:`aspose.slides.IGlobalLayoutSlideCollection`. |
| [masters](/slides/python-net/aspose.slides/masters) | Returns a list of all master slides that are defined in the presentation.<br/>            Read-only :py:class:`aspose.slides.IMasterSlideCollection`. |
| [master_notes_slide_manager](/slides/python-net/aspose.slides/master_notes_slide_manager) | Returns notes master manager.<br/>            Read-only :py:class:`aspose.slides.IMasterNotesSlideManager`. |
| [master_handout_slide_manager](/slides/python-net/aspose.slides/master_handout_slide_manager) | Returns handout master manager.<br/>            Read-only :py:class:`aspose.slides.IMasterHandoutSlideManager`. |
| [fonts_manager](/slides/python-net/aspose.slides/fonts_manager) | Returns fonts manager.<br/>            Read-only :py:class:`aspose.slides.IFontsManager`. |
| [default_text_style](/slides/python-net/aspose.slides/default_text_style) | Returns default text style for shapes.<br/>            Read-only :py:class:`aspose.slides.ITextStyle`. |
| [comment_authors](/slides/python-net/aspose.slides/comment_authors) | Returns the collection of comments autors.<br/>            Read-only :py:class:`aspose.slides.ICommentAuthorCollection`. |
| [document_properties](/slides/python-net/aspose.slides/document_properties) | Returns DocumentProperties object which contains standard and custom document properties.<br/>            Read-only :py:class:`aspose.slides.IDocumentProperties`. |
| [images](/slides/python-net/aspose.slides/images) | Returns the collection of all images in the presentation.<br/>            Read-only :py:class:`aspose.slides.IImageCollection`. |
| [audios](/slides/python-net/aspose.slides/audios) | Returns the collection of all embedded audio files in the presentation.<br/>            Read-only :py:class:`aspose.slides.IAudioCollection`. |
| [videos](/slides/python-net/aspose.slides/videos) | Returns the collection of all embedded video files in the presentation.<br/>            Read-only :py:class:`aspose.slides.IVideoCollection`. |
| [slide_show_settings](/slides/python-net/aspose.slides/slide_show_settings) | Returns the slide show settings for the presentation. |
| [digital_signatures](/slides/python-net/aspose.slides/digital_signatures) | Returns the collection of signatures used to sign the presentation.<br/>            Read-only :py:class:`aspose.slides.IDigitalSignatureCollection`. |
| [custom_data](/slides/python-net/aspose.slides/custom_data) | Returns the presentation's custom data.<br/>            Read-only :py:class:`aspose.slides.ICustomData`. |
| [all_custom_xml_parts](/slides/python-net/aspose.slides/all_custom_xml_parts) | Returns all custom data parts in the presentaion.<br/>            Read-only :py:class:`aspose.slides.ICustomXmlPart`[]. |
| [vba_project](/slides/python-net/aspose.slides/vba_project) | Gets or sets VBA project with presentation macros.<br/>            Read/write :py:class:`aspose.slides.vba.IVbaProject`. |
| [hyperlink_queries](/slides/python-net/aspose.slides/hyperlink_queries) | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides).<br/>            Read-only :py:class:`aspose.slides.IHyperlinkQueries`. |
| [view_properties](/slides/python-net/aspose.slides/view_properties) | Gets presentation wide view properties.<br/>            Read-only :py:class:`aspose.slides.IViewProperties`. |
| [first_slide_number](/slides/python-net/aspose.slides/first_slide_number) | Represents the first slide number in the presentation |
| [source_format](/slides/python-net/aspose.slides/source_format) | Returns information about from which format presentation was loaded.<br/>            Read-only :py:enum:`aspose.slides.SourceFormat`. |
| [master_theme](/slides/python-net/aspose.slides/master_theme) | Returns master theme.<br/>            Read-only :py:class:`aspose.slides.theme.IMasterTheme`. |
| [as_i_disposable](/slides/python-net/aspose.slides/as_i_disposable) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/as_i_presentation_component) |  |
| [presentation](/slides/python-net/aspose.slides/presentation) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/presentation/#string-aspose.slides.export.SaveFormat) | Saves all slides of a presentation to a file with the specified format. |
| [__init__](/slides/python-net/aspose.slides/presentation/#System.IO.Stream-aspose.slides.export.SaveFormat) | Saves all slides of a presentation to a stream in the specified format. |
| [__init__](/slides/python-net/aspose.slides/presentation/#string-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions) |  |
| [__init__](/slides/python-net/aspose.slides/presentation/#System.IO.Stream-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.xaml.IXamlOptions) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [__init__](/slides/python-net/aspose.slides/presentation/#string-List[int]-aspose.slides.export.SaveFormat) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [__init__](/slides/python-net/aspose.slides/presentation/#string-List[int]-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [__init__](/slides/python-net/aspose.slides/presentation/#System.IO.Stream-List[int]-aspose.slides.export.SaveFormat) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [__init__](/slides/python-net/aspose.slides/presentation/#System.IO.Stream-List[int]-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.INotesCommentsLayoutingOptions) | Returns a Thumbnail Bitmap objects for all slides of a presentation. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.INotesCommentsLayoutingOptions-List[int]) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.INotesCommentsLayoutingOptions-float-float) | Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.INotesCommentsLayoutingOptions-List[int]-float-float) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.INotesCommentsLayoutingOptions-List[int]-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.IRenderingOptions) | Returns a Thumbnail Bitmap objects for all slides of a presentation. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.IRenderingOptions-List[int]) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.IRenderingOptions-float-float) | Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.IRenderingOptions-List[int]-float-float) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.slides.export.IRenderingOptions-List[int]-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| [__init__](/slides/python-net/aspose.slides/presentation/#) | Prints the whole presentation to the default printer. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.pydrawing.Printing.PrinterSettings) | Prints the presentation according to the specified printer settings,<br/>            using the standard (no User Interface) print controller. |
| [__init__](/slides/python-net/aspose.slides/presentation/#string) | Print the whole presentation to the specified printer,<br/>            using the standard (no User Interface) print controller. |
| [__init__](/slides/python-net/aspose.slides/presentation/#aspose.pydrawing.Printing.PrinterSettings-string) | Prints the document according to the specified printer settings, using<br/>            the standard (no User Interface) print controller and a presentation name. |
| [__init__](/slides/python-net/aspose.slides/presentation/#int) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [__init__](/slides/python-net/aspose.slides/presentation/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |

