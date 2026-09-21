---
title: ISVGOptions class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/isvgoptions/
---
## ISVGOptions क्लास

Represents an SVG options.

The ISVGOptions type exposes the following members:

## प्रॉपर्टीज़

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`vectorize_text`](/slides/python-net/hi/aspose.slides.export/isvgoptions/vectorize_text/) | Determines whether the text on a slide will be saved as graphics.<br/>            पढ़ें/लिखें **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/hi/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Returns or sets the lower resolution limit for metafile rasterization.<br/>            पढ़ें/लिखें **int**. |
| [`disable_3d_text`](/slides/python-net/hi/aspose.slides.export/isvgoptions/disable_3d_text/) | Determines whether the 3D text is disabled in SVG.<br/>            पढ़ें/लिखें **bool**. |
| [`disable_gradient_split`](/slides/python-net/hi/aspose.slides.export/isvgoptions/disable_gradient_split/) | Disables splitting FromCornerX and FromCenter gradients.<br/>            पढ़ें/लिखें **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/hi/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 lacks ability to define insets for markers.<br/>            Aspose.Slides SVG writing engine has workaround for that problem:<br/>            it crops end of line with arrow, so, line doesn't overlap markers.<br/>            This option switches off such behavior.<br/>            पढ़ें/लिखें **bool**. |
| [`jpeg_quality`](/slides/python-net/hi/aspose.slides.export/isvgoptions/jpeg_quality/) | Determines JPEG encoding quality.<br/>            पढ़ें/लिखें **int**. |
| [`shape_formatting_controller`](/slides/python-net/hi/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Returns and sets a callback interface which allows user to control shape conversion.<br/>            पढ़ें/लिखें [`ISvgShapeFormattingController`](/slides/python-net/hi/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/hi/aspose.slides.export/isvgoptions/pictures_compression/) | Represents the pictures compression level<br/>            पढ़ें/लिखें [`ISVGOptions.pictures_compression`](/slides/python-net/hi/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/hi/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped <br/>            parts will removed, if false they will be serialized in the document (which can possible lead to a <br/>            larger file)<br/>            पढ़ें/लिखें **bool**. |
| [`use_frame_size`](/slides/python-net/hi/aspose.slides.export/isvgoptions/use_frame_size/) | Determines whether the text frame will be included in a rendering area or not.<br/>            पढ़ें/लिखें **bool**.<br/>            Default value is false. |
| [`use_frame_rotation`](/slides/python-net/hi/aspose.slides.export/isvgoptions/use_frame_rotation/) | Determines whether to perform the specified rotation of the shape when rendering or not.<br/>            पढ़ें/लिखें **bool**.<br/>            Default value is true. |
| [`external_fonts_handling`](/slides/python-net/hi/aspose.slides.export/isvgoptions/external_fonts_handling/) | Determines a way of handling externally loaded fonts.<br/>            पढ़ें/लिखें [`SvgExternalFontsHandling`](/slides/python-net/hi/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/hi/aspose.slides.export/isvgoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            केवल-पढ़ने योग्य [`IInkOptions`](/slides/python-net/hi/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/hi/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Gets or sets a value indicating whether text is rendered without using ligatures.<br/>            When set to `true`, ligatures will be disabled in the rendered output. By default, this property is set to `false`. |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### देखें
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)