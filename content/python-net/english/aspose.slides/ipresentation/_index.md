---
title: IPresentation
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ipresentation/
---


IPresentation class

Presentation document

The IPresentation type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [current_date_time](/slides/python-net/aspose.slides/ipresentation/current_date_time/) | Returns or sets date and time which will substitute content of datetime fields.<br/>            Time of this Presentation object creation by default.<br/>            Read/write :py:class:`System.DateTime`. |
| [header_footer_manager](/slides/python-net/aspose.slides/ipresentation/header_footer_manager/) | Returns HeaderFooter manager of the presentation.<br/>            Read-only :py:class:`aspose.slides.IPresentationHeaderFooterManager`. |
| [protection_manager](/slides/python-net/aspose.slides/ipresentation/protection_manager/) | Gets manager of the permissions for this presentation. <br/>            Read-only :py:class:`aspose.slides.IProtectionManager`. |
| [slides](/slides/python-net/aspose.slides/ipresentation/slides/) | Returns a list of all slides that are defined in the presentation.<br/>            Read-only :py:class:`aspose.slides.ISlideCollection`. |
| [sections](/slides/python-net/aspose.slides/ipresentation/sections/) | Returns a list of all slides sections that are defined in the presentation.<br/>            Read-only :py:class:`aspose.slides.ISectionCollection`. |
| [slide_size](/slides/python-net/aspose.slides/ipresentation/slide_size/) | Returns slide size object.<br/>            Read-only :py:class:`aspose.slides.ISlideSize`. |
| [notes_size](/slides/python-net/aspose.slides/ipresentation/notes_size/) | Returns notes slide size object.<br/>            Read-only :py:class:`aspose.slides.INotesSize`. |
| [layout_slides](/slides/python-net/aspose.slides/ipresentation/layout_slides/) | Returns a list of all layout slides that are defined in the presentation.<br/>            Read-only :py:class:`aspose.slides.IGlobalLayoutSlideCollection`. |
| [masters](/slides/python-net/aspose.slides/ipresentation/masters/) | Returns a list of all master slides that are defined in the presentation.<br/>            Read-only :py:class:`aspose.slides.IMasterSlideCollection`. |
| [master_notes_slide_manager](/slides/python-net/aspose.slides/ipresentation/master_notes_slide_manager/) | Returns notes master manager.<br/>            Read-only :py:class:`aspose.slides.IMasterNotesSlideManager`. |
| [master_handout_slide_manager](/slides/python-net/aspose.slides/ipresentation/master_handout_slide_manager/) | Returns handout master manager.<br/>            Read-only :py:class:`aspose.slides.IMasterHandoutSlideManager`. |
| [fonts_manager](/slides/python-net/aspose.slides/ipresentation/fonts_manager/) | Returns fonts manager.<br/>            Read-only :py:class:`aspose.slides.IFontsManager`. |
| [default_text_style](/slides/python-net/aspose.slides/ipresentation/default_text_style/) | Returns default text style for shapes.<br/>            Read-only :py:class:`aspose.slides.ITextStyle`. |
| [comment_authors](/slides/python-net/aspose.slides/ipresentation/comment_authors/) | Returns the collection of comments autors.<br/>            Read-only :py:class:`aspose.slides.ICommentAuthorCollection`. |
| [document_properties](/slides/python-net/aspose.slides/ipresentation/document_properties/) | Returns DocumentProperties object which contains standard and custom document properties.<br/>            Read-only :py:class:`aspose.slides.IDocumentProperties`. |
| [images](/slides/python-net/aspose.slides/ipresentation/images/) | Returns the collection of all images in the presentation.<br/>            Read-only :py:class:`aspose.slides.IImageCollection`. |
| [audios](/slides/python-net/aspose.slides/ipresentation/audios/) | Returns the collection of all embedded audio files in the presentation.<br/>            Read-only :py:class:`aspose.slides.IAudioCollection`. |
| [videos](/slides/python-net/aspose.slides/ipresentation/videos/) | Returns the collection of all embedded video files in the presentation.<br/>            Read-only :py:class:`aspose.slides.IVideoCollection`. |
| [custom_data](/slides/python-net/aspose.slides/ipresentation/custom_data/) | Returns the presentation's custom data.<br/>            Read-only :py:class:`aspose.slides.ICustomData`. |
| [vba_project](/slides/python-net/aspose.slides/ipresentation/vba_project/) | Gets VBA project with presentation macros.<br/>            Read/write :py:class:`aspose.slides.vba.IVbaProject`. |
| [source_format](/slides/python-net/aspose.slides/ipresentation/source_format/) | Returns information about from which format presentation was loaded.<br/>            Read-only :py:attr:`aspose.slides.IPresentation.source_format`. |
| [master_theme](/slides/python-net/aspose.slides/ipresentation/master_theme/) | Returns master theme of the presentation.<br/>            Read-only :py:class:`aspose.slides.theme.IMasterTheme`. |
| [hyperlink_queries](/slides/python-net/aspose.slides/ipresentation/hyperlink_queries/) | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides).<br/>            Read-only :py:class:`aspose.slides.IHyperlinkQueries`. |
| [view_properties](/slides/python-net/aspose.slides/ipresentation/view_properties/) | Gets presentation wide view properties.<br/>            Read-only :py:class:`aspose.slides.IViewProperties`. |
| [first_slide_number](/slides/python-net/aspose.slides/ipresentation/first_slide_number/) | Represents the first slide number in the presentation.<br/>            Read/write :py:class:`int`. |
| [all_custom_xml_parts](/slides/python-net/aspose.slides/ipresentation/all_custom_xml_parts/) | Returns all custom data parts in the presentaion.<br/>            Read-only :py:class:`aspose.slides.ICustomXmlPart`[]. |
| [digital_signatures](/slides/python-net/aspose.slides/ipresentation/digital_signatures/) | Returns the collection of signatures used to sign the presentation.<br/>            Read-only :py:class:`aspose.slides.IDigitalSignatureCollection`. |
| [as_i_disposable](/slides/python-net/aspose.slides/ipresentation/as_i_disposable/) | Returns IDisposable interface.<br/>            Read-only :py:class:`System.IDisposable`. |
| [as_i_presentation_component](/slides/python-net/aspose.slides/ipresentation/as_i_presentation_component/) | Allows to get base IPresentationComponent interface.<br/>            Read-only :py:class:`aspose.slides.IPresentationComponent`. |
| [presentation](/slides/python-net/aspose.slides/ipresentation/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [save](/slides/python-net/aspose.slides/ipresentation/ipresentation/#string-aspose.slides.export.SaveFormat/) | Saves all slides of a presentation to a file with the specified format. |
| [save](/slides/python-net/aspose.slides/ipresentation/ipresentation/#System.IO.Stream-aspose.slides.export.SaveFormat/) | Saves all slides of a presentation to a stream in the specified format. |
| [save](/slides/python-net/aspose.slides/ipresentation/ipresentation/#string-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions/) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](/slides/python-net/aspose.slides/ipresentation/ipresentation/#System.IO.Stream-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions/) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](/slides/python-net/aspose.slides/ipresentation/ipresentation/#string-List[int]-aspose.slides.export.SaveFormat/) | Saves specified slides of a presentation to a file with the specified format. |
| [save](/slides/python-net/aspose.slides/ipresentation/ipresentation/#string-List[int]-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions/) | Saves specified slides of a presentation to a file with the specified format. |
| [save](/slides/python-net/aspose.slides/ipresentation/ipresentation/#System.IO.Stream-List[int]-aspose.slides.export.SaveFormat/) | Saves specified slides of a presentation to a stream in the specified format. |
| [save](/slides/python-net/aspose.slides/ipresentation/ipresentation/#System.IO.Stream-List[int]-aspose.slides.export.SaveFormat-aspose.slides.export.ISaveOptions/) | Saves specified slides of a presentation to a stream in the specified format. |
| [save](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.xaml.IXamlOptions/) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.INotesCommentsLayoutingOptions/) | Returns a Thumbnail Bitmap objects for all slides of a presentation. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.INotesCommentsLayoutingOptions-List[int]/) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.INotesCommentsLayoutingOptions-float-float/) | Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.INotesCommentsLayoutingOptions-List[int]-float-float/) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Size/) | Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.INotesCommentsLayoutingOptions-List[int]-aspose.pydrawing.Size/) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.IRenderingOptions/) | Returns a Thumbnail Bitmap objects for all slides of a presentation. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.IRenderingOptions-List[int]/) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.IRenderingOptions-float-float/) | Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.IRenderingOptions-List[int]-float-float/) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Size/) | Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size. |
| [get_thumbnails](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.slides.export.IRenderingOptions-List[int]-aspose.pydrawing.Size/) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| [print](/slides/python-net/aspose.slides/ipresentation/ipresentation/#/) | Prints the whole presentation to the default printer. |
| [print](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.pydrawing.Printing.PrinterSettings/) | Prints the presentation according to the specified printer settings,<br/>            using the standard (no User Interface) print controller. |
| [print](/slides/python-net/aspose.slides/ipresentation/ipresentation/#string/) | Print the whole presentation to the specified printer,<br/>            using the standard (no User Interface) print controller. |
| [print](/slides/python-net/aspose.slides/ipresentation/ipresentation/#aspose.pydrawing.Printing.PrinterSettings-string/) | Prints the document according to the specified printer settings, using<br/>            the standard (no User Interface) print controller and a presentation name. |
| [get_slide_by_id](/slides/python-net/aspose.slides/ipresentation/ipresentation/#int/) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/ipresentation/ipresentation/#/) | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |

