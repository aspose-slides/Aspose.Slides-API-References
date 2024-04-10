---
title: HtmlOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/
---


## HtmlOptions class

Represents a HTML exporting options.

**Inheritance:**[`HtmlOptions`](/slides/python-net/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The HtmlOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.export/htmloptions/#ILinkEmbedController) | Creates a new HtmlOptions object specifiing callback. |
| [__init__](/slides/python-net/aspose.slides.export/htmloptions/#) | Creates a new HtmlOptions object for saving into single HTML file. |

## Properties

| Property | Description |
| :- | :- |
| [warning_callback](/slides/python-net/aspose.slides.export/warning_callback) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write :py:class:`aspose.slides.warnings.IWarningCallback`. |
| [progress_callback](/slides/python-net/aspose.slides.export/progress_callback) | Represents a callback object for saving progress updates in percentage.<br/>            See :py:class:`aspose.slides.IProgressCallback`. |
| [default_regular_font](/slides/python-net/aspose.slides.export/default_regular_font) | Returns or sets font used in case source font is not found.<br/>            Read-write :py:class:`System.String`. |
| [slides_layout_options](/slides/python-net/aspose.slides.export/slides_layout_options) | Gets or sets the mode in which slides are placed on the page when exporting a presentation :py:class:`aspose.slides.export.ISlidesLayoutOptions`. |
| [ink_options](/slides/python-net/aspose.slides.export/ink_options) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only :py:class:`aspose.slides.export.IInkOptions` |
| [notes_comments_layouting](/slides/python-net/aspose.slides.export/notes_comments_layouting) | Provides options that control how notes and comments is placed in exported document. |
| [show_hidden_slides](/slides/python-net/aspose.slides.export/show_hidden_slides) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is ``false``. |
| [html_formatter](/slides/python-net/aspose.slides.export/html_formatter) | Returns or sets HTML template.<br/>            Read/write :py:class:`aspose.slides.export.IHtmlFormatter`. |
| [slide_image_format](/slides/python-net/aspose.slides.export/slide_image_format) | Returns or sets slide image format options.<br/>            Read/write :py:class:`aspose.slides.export.ISlideImageFormat`. |
| [jpeg_quality](/slides/python-net/aspose.slides.export/jpeg_quality) | Returns or sets a value determining the quality of the JPEG images inside PDF document.<br/>            Read/write :py:class:`int`. |
| [pictures_compression](/slides/python-net/aspose.slides.export/pictures_compression) | Represents the pictures compression level |
| [delete_pictures_cropped_areas](/slides/python-net/aspose.slides.export/delete_pictures_cropped_areas) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped <br/>            parts will removed, if false they will be serialized in the document (which can possible lead to a <br/>            larger file) |
| [svg_responsive_layout](/slides/python-net/aspose.slides.export/svg_responsive_layout) | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise.<br/>            Read/write :py:class:`bool`. |
| [as_i_save_options](/slides/python-net/aspose.slides.export/as_i_save_options) |  |

