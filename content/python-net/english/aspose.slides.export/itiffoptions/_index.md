---
title: ITiffOptions
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/itiffoptions/
---


ITiffOptions class

Provides options that control how a presentation is saved in TIFF format.

The ITiffOptions type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [image_size](/slides/python-net/aspose.slides.export/itiffoptions/image_size/) | Specifies size of a generated TIFF image.<br/>            Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value.<br/>            Read/write <br/>.NET type System.Drawing.Size. |
| [dpi_x](/slides/python-net/aspose.slides.export/itiffoptions/dpi_x/) | Specifies the horizontal resolution in dots per inch.<br/>            Read/write <br/>.NET type System.UInt32. |
| [dpi_y](/slides/python-net/aspose.slides.export/itiffoptions/dpi_y/) | Specifies the vertical resolution in dots per inch.<br/>            Read/write <br/>.NET type System.UInt32. |
| [show_hidden_slides](/slides/python-net/aspose.slides.export/itiffoptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is <br/>`false<br/>`. |
| [compression_type](/slides/python-net/aspose.slides.export/itiffoptions/compression_type/) | Specifies the compression type.<br/>            Read/write <br/>[`TiffCompressionTypes`](/slides/python-net/aspose.slides.export/tiffcompressiontypes). |
| [pixel_format](/slides/python-net/aspose.slides.export/itiffoptions/pixel_format/) | Specifies the pixel format for the generated images.<br/>            Read/write <br/>[`ImagePixelFormat`](/slides/python-net/aspose.slides.export/imagepixelformat). |
| [notes_comments_layouting](/slides/python-net/aspose.slides.export/itiffoptions/notes_comments_layouting/) | Provides options that control how notes and comments is placed in exported document. |
| [slides_layout_options](/slides/python-net/aspose.slides.export/itiffoptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation <br/>[`ISlidesLayoutOptions`](/slides/python-net/aspose.slides.export/islideslayoutoptions). |
| [bw_conversion_mode](/slides/python-net/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Specifies the algorithm for converting a color image into a black and white image.<br/>            This option will applied only if <br/>[`ITiffOptions.compression_type`](/slides/python-net/aspose.slides.export/itiffoptions#compression_type) <br/>            is set to <br/>[`TiffCompressionTypes.CCITT4`](/slides/python-net/aspose.slides.export/tiffcompressiontypes#CCITT4) or <br/>[`TiffCompressionTypes.CCITT3`](/slides/python-net/aspose.slides.export/tiffcompressiontypes#CCITT3)<br/>            Read/write <br/>[`BlackWhiteConversionMode`](/slides/python-net/aspose.slides.export/blackwhiteconversionmode).<br/>            Default is <br/>[`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/aspose.slides.export/blackwhiteconversionmode#DEFAULT). |
| [ink_options](/slides/python-net/aspose.slides.export/itiffoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only <br/>[`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |
| [as_i_save_options](/slides/python-net/aspose.slides.export/itiffoptions/as_i_save_options/) | Returns ISaveOptions interface.<br/>            Read-only <br/>[`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions). |
| [warning_callback](/slides/python-net/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [progress_callback](/slides/python-net/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [default_regular_font](/slides/python-net/aspose.slides.export/itiffoptions/default_regular_font/) |  |

