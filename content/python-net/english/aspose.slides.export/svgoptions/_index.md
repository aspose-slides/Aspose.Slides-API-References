﻿---
title: SVGOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/svgoptions/
---


## SVGOptions class

Represents an SVG options.

**Inheritance:**[`SVGOptions`](/slides/python-net/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The SVGOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.export/svgoptions/__init__/#) | Initializes a new instance of the SVGOptions class. |
| [`__init__`](/slides/python-net/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

## Properties

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/aspose.slides.export/svgoptions/warning_callback/) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/aspose.slides.export/svgoptions/progress_callback/) | Represents a callback object for saving progress updates in percentage.<br/>            See [`IProgressCallback`](/slides/python-net/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/aspose.slides.export/svgoptions/default_regular_font/) | Returns or sets font used in case source font is not found.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/aspose.slides.export/svgoptions/gradient_style/) | Returns or sets the visual style of the gradient.<br/>            Read/write [`GradientStyle`](/slides/python-net/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/aspose.slides.export/svgoptions/skip_java_script_links/) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. <br/>            Read/write **bool**. The default value is **false** . |
| [`ink_options`](/slides/python-net/aspose.slides.export/svgoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only [`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/aspose.slides.export/svgoptions/use_frame_size/) | Determines whether the text frame will be included in a rendering area or not.<br/>            Read/write **bool**.<br/>            Default value is false. |
| [`use_frame_rotation`](/slides/python-net/aspose.slides.export/svgoptions/use_frame_rotation/) | Determines whether to perform the specified rotation of the shape when rendering or not.<br/>            Read/write **bool**.<br/>            Default value is true. |
| [`vectorize_text`](/slides/python-net/aspose.slides.export/svgoptions/vectorize_text/) | Determines whether the text on a slide will be saved as graphics.<br/>            Read/write **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Returns or sets the lower resolution limit for metafile rasterization.<br/>            Read/write **int**. |
| [`disable_3d_text`](/slides/python-net/aspose.slides.export/svgoptions/disable_3d_text/) | Determines whether the 3D text is disabled in SVG.<br/>            Read/write **bool**. |
| [`disable_gradient_split`](/slides/python-net/aspose.slides.export/svgoptions/disable_gradient_split/) | Disables splitting FromCornerX and FromCenter gradients.<br/>            Read/write **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 lacks ability to define insets for markers.<br/>            Aspose.Slides SVG writing engine has workaround for that problem:<br/>            it crops end of line with arrow, so, line doesn't overlap markers.<br/>            This option switches off such behavior.<br/>            Read/write **bool**. |
| [`default`](/slides/python-net/aspose.slides.export/svgoptions/default/) | Returns default settings.<br/>            Read-only [`SVGOptions`](/slides/python-net/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/aspose.slides.export/svgoptions/simple/) | Returns settings for simpliest and smallest SVG file generation.<br/>            Read-only [`SVGOptions`](/slides/python-net/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/aspose.slides.export/svgoptions/wysiwyg/) | Returns settings for most accurate SVG file generation.<br/>            Read-only [`SVGOptions`](/slides/python-net/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/aspose.slides.export/svgoptions/jpeg_quality/) | Determines JPEG encoding quality.<br/>            Read/write **int**. |
| [`shape_formatting_controller`](/slides/python-net/aspose.slides.export/svgoptions/shape_formatting_controller/) | Returns and sets a callback interface which allows user to control shape conversion.<br/>            Read/write [`ISvgShapeFormattingController`](/slides/python-net/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/aspose.slides.export/svgoptions/pictures_compression/) | Represents the pictures compression level |
| [`delete_pictures_cropped_areas`](/slides/python-net/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped <br/>            parts will removed, if false they will be serialized in the document (which can possible lead to a <br/>            larger file) |
| [`external_fonts_handling`](/slides/python-net/aspose.slides.export/svgoptions/external_fonts_handling/) | Determines a way of handling externally loaded fonts.<br/>            Read/write [`SvgExternalFontsHandling`](/slides/python-net/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/aspose.slides.export/svgoptions/disable_font_ligatures/) | Gets or sets a value indicating whether text is rendered without using ligatures.<br/>            When set to `true`, ligatures will be disabled in the rendered output. By default, this property is set to `false`. |


### See Also
* class [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)
* class [`SVGOptions`](/slides/python-net/aspose.slides.export/svgoptions)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

