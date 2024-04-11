---
title: ISVGOptions
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/isvgoptions/
---


ISVGOptions class

Represents an SVG options.

The ISVGOptions type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [vectorize_text](/slides/python-net/aspose.slides.export/isvgoptions/vectorize_text/) | Determines whether the text on a slide will be saved as graphics.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [metafile_rasterization_dpi](/slides/python-net/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Returns or sets the lower resolution limit for metafile rasterization.<br/>            Read/write <br/>.NET type System.Int32<br/>. |
| [disable_3d_text](/slides/python-net/aspose.slides.export/isvgoptions/disable_3d_text/) | Determines whether the 3D text is disabled in SVG.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [disable_gradient_split](/slides/python-net/aspose.slides.export/isvgoptions/disable_gradient_split/) | Disables splitting FromCornerX and FromCenter gradients.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [disable_line_end_cropping](/slides/python-net/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 lacks ability to define insets for markers.<br/>            Aspose.Slides SVG writing engine has workaround for that problem:<br/>            it crops end of line with arrow, so, line doesn't overlap markers.<br/>            This option switches off such behavior.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [jpeg_quality](/slides/python-net/aspose.slides.export/isvgoptions/jpeg_quality/) | Determines JPEG encoding quality.<br/>            Read/write <br/>.NET type System.Int32<br/>. |
| [shape_formatting_controller](/slides/python-net/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Returns and sets a callback interface which allows user to control shape conversion.<br/>            Read/write <br/>[`ISvgShapeFormattingController`](/slides/python-net/aspose.slides.export/isvgshapeformattingcontroller)<br/>. |
| [pictures_compression](/slides/python-net/aspose.slides.export/isvgoptions/pictures_compression/) | Represents the pictures compression level<br/>            Read/write <br/>[`ISVGOptions.pictures_compression`](/slides/python-net/aspose.slides.export/isvgoptions#pictures_compression)<br/>. |
| [delete_pictures_cropped_areas](/slides/python-net/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped <br/>            parts will removed, if false they will be serialized in the document (which can possible lead to a <br/>            larger file)<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [use_frame_size](/slides/python-net/aspose.slides.export/isvgoptions/use_frame_size/) | Determines whether the text frame will be included in a rendering area or not.<br/>            Read/write <br/>.NET type System.Boolean<br/>.<br/>            Default value is false. |
| [use_frame_rotation](/slides/python-net/aspose.slides.export/isvgoptions/use_frame_rotation/) | Determines whether to perform the specified rotation of the shape when rendering or not.<br/>            Read/write <br/>.NET type System.Boolean<br/>.<br/>            Default value is true. |
| [external_fonts_handling](/slides/python-net/aspose.slides.export/isvgoptions/external_fonts_handling/) | Determines a way of handling externally loaded fonts.<br/>            Read/write <br/>[`SvgExternalFontsHandling`](/slides/python-net/aspose.slides.export/svgexternalfontshandling)<br/>. |
| [ink_options](/slides/python-net/aspose.slides.export/isvgoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only <br/>[`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |
| [as_i_save_options](/slides/python-net/aspose.slides.export/isvgoptions/as_i_save_options/) | Returns ISaveOptions interface.<br/>            Read-only <br/>[`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions)<br/>. |
| [warning_callback](/slides/python-net/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [progress_callback](/slides/python-net/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [default_regular_font](/slides/python-net/aspose.slides.export/isvgoptions/default_regular_font/) |  |

