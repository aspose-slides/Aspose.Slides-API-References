---
title: ITiffOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/itiffoptions/
---


## ITiffOptions class

Provides options that control how a presentation is saved in TIFF format.

The ITiffOptions type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`image_size`](/slides/python-net/aspose.slides.export/itiffoptions/image_size/) | Specifies size of a generated TIFF image.<br/>            Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value.<br/>            Read/write **aspose.pydrawing.Size**. |
| [`dpi_x`](/slides/python-net/aspose.slides.export/itiffoptions/dpi_x/) | Specifies the horizontal resolution in dots per inch.<br/>            Read/write **int**. |
| [`dpi_y`](/slides/python-net/aspose.slides.export/itiffoptions/dpi_y/) | Specifies the vertical resolution in dots per inch.<br/>            Read/write **int**. |
| [`show_hidden_slides`](/slides/python-net/aspose.slides.export/itiffoptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is `false`. |
| [`compression_type`](/slides/python-net/aspose.slides.export/itiffoptions/compression_type/) | Specifies the compression type.<br/>            Read/write [`TiffCompressionTypes`](/slides/python-net/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/aspose.slides.export/itiffoptions/pixel_format/) | Specifies the pixel format for the generated images.<br/>            Read/write [`ImagePixelFormat`](/slides/python-net/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/aspose.slides.export/itiffoptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](/slides/python-net/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Specifies the algorithm for converting a color image into a black and white image.<br/>            This option will applied only if [`ITiffOptions.compression_type`](/slides/python-net/aspose.slides.export/itiffoptions/compression_type) <br/>            is set to [`TiffCompressionTypes.CCITT4`](/slides/python-net/aspose.slides.export/tiffcompressiontypes/CCITT4) or [`TiffCompressionTypes.CCITT3`](/slides/python-net/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Read/write [`BlackWhiteConversionMode`](/slides/python-net/aspose.slides.export/blackwhiteconversionmode).<br/>            Default is [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/aspose.slides.export/itiffoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only [`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/aspose.slides.export/itiffoptions/gradient_style/) |  |


### See Also
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

