---
title: TiffOptions
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/tiffoptions/
---


TiffOptions class

Provides options that control how a presentation is saved in TIFF format.

**Inheritance:**[`TiffOptions`](/slides/python-net/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The TiffOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.export/tiffoptions/tiffoptions/#/) | Default constructor. |

## Properties

| Property | Description |
| :- | :- |
| [warning_callback](/slides/python-net/aspose.slides.export/tiffoptions/warning_callback/) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write :py:class:`aspose.slides.warnings.IWarningCallback`. |
| [progress_callback](/slides/python-net/aspose.slides.export/tiffoptions/progress_callback/) | Represents a callback object for saving progress updates in percentage.<br/>            See :py:class:`aspose.slides.IProgressCallback`. |
| [default_regular_font](/slides/python-net/aspose.slides.export/tiffoptions/default_regular_font/) | Returns or sets font used in case source font is not found.<br/>            Read-write :py:class:`System.String`. |
| [ink_options](/slides/python-net/aspose.slides.export/tiffoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only :py:class:`aspose.slides.export.IInkOptions` |
| [notes_comments_layouting](/slides/python-net/aspose.slides.export/tiffoptions/notes_comments_layouting/) | Provides options that control how notes and comments is placed in exported document. |
| [show_hidden_slides](/slides/python-net/aspose.slides.export/tiffoptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is ``false``. |
| [image_size](/slides/python-net/aspose.slides.export/tiffoptions/image_size/) | Specifies size of a generated TIFF image.<br/>            Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value.<br/>            Read/write :py:class:`aspose.pydrawing.Size`. |
| [dpi_x](/slides/python-net/aspose.slides.export/tiffoptions/dpi_x/) | Specifies the horizontal resolution in dots per inch.<br/>            Read/write :py:class:`int`. |
| [dpi_y](/slides/python-net/aspose.slides.export/tiffoptions/dpi_y/) | Specifies the vertical resolution in dots per inch.<br/>            Read/write :py:class:`int`. |
| [compression_type](/slides/python-net/aspose.slides.export/tiffoptions/compression_type/) | Specifies the compression type.<br/>            Read/write :py:enum:`aspose.slides.export.TiffCompressionTypes`. |
| [pixel_format](/slides/python-net/aspose.slides.export/tiffoptions/pixel_format/) | Specifies the pixel format for the generated images.<br/>            Read/write :py:enum:`aspose.slides.export.ImagePixelFormat`. |
| [slides_layout_options](/slides/python-net/aspose.slides.export/tiffoptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation :py:class:`aspose.slides.export.ISlidesLayoutOptions`. |
| [bw_conversion_mode](/slides/python-net/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Specifies the algorithm for converting a color image into a black and white image.<br/>            This option will applied only if :py:attr:`aspose.slides.export.TiffOptions.compression_type` <br/>            is set to :py:attr:`aspose.slides.export.TiffCompressionTypes.CCITT4` or :py:attr:`aspose.slides.export.TiffCompressionTypes.CCITT3`<br/>            Read/write :py:enum:`aspose.slides.export.BlackWhiteConversionMode`.<br/>            Default is :py:attr:`aspose.slides.export.BlackWhiteConversionMode.DEFAULT`. |
| [as_i_save_options](/slides/python-net/aspose.slides.export/tiffoptions/as_i_save_options/) |  |

