---
title: SVGOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/
---


## SVGOptions class

Represents an SVG options.

**Inheritance:**[`SVGOptions`](/slides/python-net/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The SVGOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.export/svgoptions/#) | Initializes a new instance of the SVGOptions class. |
| [__init__](/slides/python-net/aspose.slides.export/svgoptions/#ILinkEmbedController) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

## Properties

| Property | Description |
| :- | :- |
| [warning_callback](/slides/python-net/aspose.slides.export/warning_callback) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write :py:class:`aspose.slides.warnings.IWarningCallback`. |
| [progress_callback](/slides/python-net/aspose.slides.export/progress_callback) | Represents a callback object for saving progress updates in percentage.<br/>            See :py:class:`aspose.slides.IProgressCallback`. |
| [default_regular_font](/slides/python-net/aspose.slides.export/default_regular_font) | Returns or sets font used in case source font is not found.<br/>            Read-write :py:class:`System.String`. |
| [ink_options](/slides/python-net/aspose.slides.export/ink_options) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only :py:class:`aspose.slides.export.IInkOptions` |
| [use_frame_size](/slides/python-net/aspose.slides.export/use_frame_size) | Determines whether the text frame will be included in a rendering area or not.<br/>            Read/write :py:class:`bool`.<br/>            Default value is false. |
| [use_frame_rotation](/slides/python-net/aspose.slides.export/use_frame_rotation) | Determines whether to perform the specified rotation of the shape when rendering or not.<br/>            Read/write :py:class:`bool`.<br/>            Default value is true. |
| [vectorize_text](/slides/python-net/aspose.slides.export/vectorize_text) | Determines whether the text on a slide will be saved as graphics.<br/>            Read/write :py:class:`bool`. |
| [metafile_rasterization_dpi](/slides/python-net/aspose.slides.export/metafile_rasterization_dpi) | Returns or sets the lower resolution limit for metafile rasterization.<br/>            Read/write :py:class:`int`. |
| [disable_3d_text](/slides/python-net/aspose.slides.export/disable_3d_text) | Determines whether the 3D text is disabled in SVG.<br/>            Read/write :py:class:`bool`. |
| [disable_gradient_split](/slides/python-net/aspose.slides.export/disable_gradient_split) | Disables splitting FromCornerX and FromCenter gradients.<br/>            Read/write :py:class:`bool`. |
| [disable_line_end_cropping](/slides/python-net/aspose.slides.export/disable_line_end_cropping) | SVG 1.1 lacks ability to define insets for markers.<br/>            Aspose.Slides SVG writing engine has workaround for that problem:<br/>            it crops end of line with arrow, so, line doesn't overlap markers.<br/>            This option switches off such behavior.<br/>            Read/write :py:class:`bool`. |
| [default](/slides/python-net/aspose.slides.export/default) | Returns default settings.<br/>            Read-only :py:class:`aspose.slides.export.SVGOptions`. |
| [simple](/slides/python-net/aspose.slides.export/simple) | Returns settings for simpliest and smallest SVG file generation.<br/>            Read-only :py:class:`aspose.slides.export.SVGOptions`. |
| [wysiwyg](/slides/python-net/aspose.slides.export/wysiwyg) | Returns settings for most accurate SVG file generation.<br/>            Read-only :py:class:`aspose.slides.export.SVGOptions`. |
| [jpeg_quality](/slides/python-net/aspose.slides.export/jpeg_quality) | Determines JPEG encoding quality.<br/>            Read/write :py:class:`int`. |
| [shape_formatting_controller](/slides/python-net/aspose.slides.export/shape_formatting_controller) | Returns and sets a callback interface which allows user to control shape conversion.<br/>            Read/write :py:class:`aspose.slides.export.ISvgShapeFormattingController`. |
| [pictures_compression](/slides/python-net/aspose.slides.export/pictures_compression) | Represents the pictures compression level |
| [delete_pictures_cropped_areas](/slides/python-net/aspose.slides.export/delete_pictures_cropped_areas) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped <br/>            parts will removed, if false they will be serialized in the document (which can possible lead to a <br/>            larger file) |
| [external_fonts_handling](/slides/python-net/aspose.slides.export/external_fonts_handling) | Determines a way of handling externally loaded fonts.<br/>            Read/write :py:enum:`aspose.slides.export.SvgExternalFontsHandling`. |
| [as_i_save_options](/slides/python-net/aspose.slides.export/as_i_save_options) |  |

