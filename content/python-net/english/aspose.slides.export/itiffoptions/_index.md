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
| [image_size](/slides/python-net/aspose.slides.export/itiffoptions/image_size/) | Specifies size of a generated TIFF image.<br/>            Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value.<br/>            Read/write :py:class:`aspose.pydrawing.Size`. |
| [dpi_x](/slides/python-net/aspose.slides.export/itiffoptions/dpi_x/) | Specifies the horizontal resolution in dots per inch.<br/>            Read/write :py:class:`int`. |
| [dpi_y](/slides/python-net/aspose.slides.export/itiffoptions/dpi_y/) | Specifies the vertical resolution in dots per inch.<br/>            Read/write :py:class:`int`. |
| [show_hidden_slides](/slides/python-net/aspose.slides.export/itiffoptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is ``false``. |
| [compression_type](/slides/python-net/aspose.slides.export/itiffoptions/compression_type/) | Specifies the compression type.<br/>            Read/write :py:enum:`aspose.slides.export.TiffCompressionTypes`. |
| [pixel_format](/slides/python-net/aspose.slides.export/itiffoptions/pixel_format/) | Specifies the pixel format for the generated images.<br/>            Read/write :py:enum:`aspose.slides.export.ImagePixelFormat`. |
| [notes_comments_layouting](/slides/python-net/aspose.slides.export/itiffoptions/notes_comments_layouting/) | Provides options that control how notes and comments is placed in exported document. |
| [slides_layout_options](/slides/python-net/aspose.slides.export/itiffoptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation :py:class:`aspose.slides.export.ISlidesLayoutOptions`. |
| [bw_conversion_mode](/slides/python-net/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Specifies the algorithm for converting a color image into a black and white image.<br/>            This option will applied only if :py:attr:`aspose.slides.export.ITiffOptions.compression_type` <br/>            is set to :py:attr:`aspose.slides.export.TiffCompressionTypes.CCITT4` or :py:attr:`aspose.slides.export.TiffCompressionTypes.CCITT3`<br/>            Read/write :py:enum:`aspose.slides.export.BlackWhiteConversionMode`.<br/>            Default is :py:attr:`aspose.slides.export.BlackWhiteConversionMode.DEFAULT`. |
| [ink_options](/slides/python-net/aspose.slides.export/itiffoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only :py:class:`aspose.slides.export.IInkOptions` |
| [as_i_save_options](/slides/python-net/aspose.slides.export/itiffoptions/as_i_save_options/) | Returns ISaveOptions interface.<br/>            Read-only :py:class:`aspose.slides.export.ISaveOptions`. |
| [warning_callback](/slides/python-net/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [progress_callback](/slides/python-net/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [default_regular_font](/slides/python-net/aspose.slides.export/itiffoptions/default_regular_font/) |  |

