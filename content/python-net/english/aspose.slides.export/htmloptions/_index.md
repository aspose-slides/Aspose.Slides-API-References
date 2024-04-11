---
title: HtmlOptions
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/htmloptions/
---


HtmlOptions class

Represents a HTML exporting options.

**Inheritance:**[`HtmlOptions`](/slides/python-net/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The HtmlOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.export/htmloptions/htmloptions/#ILinkEmbedController/) | Creates a new HtmlOptions object specifiing callback. |
| [__init__](/slides/python-net/aspose.slides.export/htmloptions/htmloptions/#/) | Creates a new HtmlOptions object for saving into single HTML file. |

## Properties

| Property | Description |
| :- | :- |
| [warning_callback](/slides/python-net/aspose.slides.export/htmloptions/warning_callback/) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write <br/>[`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback). |
| [progress_callback](/slides/python-net/aspose.slides.export/htmloptions/progress_callback/) | Represents a callback object for saving progress updates in percentage.<br/>            See <br/>[`IProgressCallback`](/slides/python-net/aspose.slides/iprogresscallback). |
| [default_regular_font](/slides/python-net/aspose.slides.export/htmloptions/default_regular_font/) | Returns or sets font used in case source font is not found.<br/>            Read-write <br/>.NET type System.String. |
| [slides_layout_options](/slides/python-net/aspose.slides.export/htmloptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation <br/>[`ISlidesLayoutOptions`](/slides/python-net/aspose.slides.export/islideslayoutoptions). |
| [ink_options](/slides/python-net/aspose.slides.export/htmloptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only <br/>[`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |
| [notes_comments_layouting](/slides/python-net/aspose.slides.export/htmloptions/notes_comments_layouting/) | Provides options that control how notes and comments is placed in exported document. |
| [show_hidden_slides](/slides/python-net/aspose.slides.export/htmloptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is <br/>`false<br/>`. |
| [html_formatter](/slides/python-net/aspose.slides.export/htmloptions/html_formatter/) | Returns or sets HTML template.<br/>            Read/write <br/>[`IHtmlFormatter`](/slides/python-net/aspose.slides.export/ihtmlformatter). |
| [slide_image_format](/slides/python-net/aspose.slides.export/htmloptions/slide_image_format/) | Returns or sets slide image format options.<br/>            Read/write <br/>[`ISlideImageFormat`](/slides/python-net/aspose.slides.export/islideimageformat). |
| [jpeg_quality](/slides/python-net/aspose.slides.export/htmloptions/jpeg_quality/) | Returns or sets a value determining the quality of the JPEG images inside PDF document.<br/>            Read/write <br/>.NET type System.Byte. |
| [pictures_compression](/slides/python-net/aspose.slides.export/htmloptions/pictures_compression/) | Represents the pictures compression level |
| [delete_pictures_cropped_areas](/slides/python-net/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped <br/>            parts will removed, if false they will be serialized in the document (which can possible lead to a <br/>            larger file) |
| [svg_responsive_layout](/slides/python-net/aspose.slides.export/htmloptions/svg_responsive_layout/) | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise.<br/>            Read/write <br/>.NET type System.Boolean. |
| [as_i_save_options](/slides/python-net/aspose.slides.export/htmloptions/as_i_save_options/) |  |

