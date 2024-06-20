---
title: TiffOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/tiffoptions/
---


## TiffOptions class

Provides options that control how a presentation is saved in TIFF format.

**Inheritance:**[`TiffOptions`](/slides/python-net/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The TiffOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.export/tiffoptions/__init__/#) | Default constructor. |

## Properties

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/aspose.slides.export/tiffoptions/warning_callback/) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/aspose.slides.export/tiffoptions/progress_callback/) | Represents a callback object for saving progress updates in percentage.<br/>            See [`IProgressCallback`](/slides/python-net/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/aspose.slides.export/tiffoptions/default_regular_font/) | Returns or sets font used in case source font is not found.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/aspose.slides.export/tiffoptions/gradient_style/) | Returns or sets the visual style of the gradient.<br/>            Read/write [`GradientStyle`](/slides/python-net/aspose.slides/gradientstyle/). |
| [`ink_options`](/slides/python-net/aspose.slides.export/tiffoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only [`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |
| [`notes_comments_layouting`](/slides/python-net/aspose.slides.export/tiffoptions/notes_comments_layouting/) | Provides options that control how notes and comments is placed in exported document. |
| [`show_hidden_slides`](/slides/python-net/aspose.slides.export/tiffoptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is `false`. |
| [`image_size`](/slides/python-net/aspose.slides.export/tiffoptions/image_size/) | Specifies size of a generated TIFF image.<br/>            Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value.<br/>            Read/write **aspose.pydrawing.Size**. |
| [`dpi_x`](/slides/python-net/aspose.slides.export/tiffoptions/dpi_x/) | Specifies the horizontal resolution in dots per inch.<br/>            Read/write **int**. |
| [`dpi_y`](/slides/python-net/aspose.slides.export/tiffoptions/dpi_y/) | Specifies the vertical resolution in dots per inch.<br/>            Read/write **int**. |
| [`compression_type`](/slides/python-net/aspose.slides.export/tiffoptions/compression_type/) | Specifies the compression type.<br/>            Read/write [`TiffCompressionTypes`](/slides/python-net/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/aspose.slides.export/tiffoptions/pixel_format/) | Specifies the pixel format for the generated images.<br/>            Read/write [`ImagePixelFormat`](/slides/python-net/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/aspose.slides.export/tiffoptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](/slides/python-net/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Specifies the algorithm for converting a color image into a black and white image.<br/>            This option will applied only if [`TiffOptions.compression_type`](/slides/python-net/aspose.slides.export/tiffoptions#compression_type) <br/>            is set to [`TiffCompressionTypes.CCITT4`](/slides/python-net/aspose.slides.export/tiffcompressiontypes#CCITT4) or [`TiffCompressionTypes.CCITT3`](/slides/python-net/aspose.slides.export/tiffcompressiontypes#CCITT3)<br/>            Read/write [`BlackWhiteConversionMode`](/slides/python-net/aspose.slides.export/blackwhiteconversionmode).<br/>            Default is [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/aspose.slides.export/blackwhiteconversionmode#DEFAULT). |


### See Also
* class [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)
* class [`TiffOptions`](/slides/python-net/aspose.slides.export/tiffoptions)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

