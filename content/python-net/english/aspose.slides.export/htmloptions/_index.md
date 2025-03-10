---
title: HtmlOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/htmloptions/
---


## HtmlOptions class

Represents a HTML exporting options.

**Inheritance:**[`HtmlOptions`](/slides/python-net/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The HtmlOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Creates a new HtmlOptions object specifiing callback. |
| [`__init__`](/slides/python-net/aspose.slides.export/htmloptions/__init__/#) | Creates a new HtmlOptions object for saving into single HTML file. |

## Properties

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/aspose.slides.export/htmloptions/warning_callback/) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/aspose.slides.export/htmloptions/progress_callback/) | Represents a callback object for saving progress updates in percentage.<br/>            See [`IProgressCallback`](/slides/python-net/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/aspose.slides.export/htmloptions/default_regular_font/) | Returns or sets font used in case source font is not found.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/aspose.slides.export/htmloptions/gradient_style/) | Returns or sets the visual style of the gradient.<br/>            Read/write [`GradientStyle`](/slides/python-net/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/aspose.slides.export/htmloptions/skip_java_script_links/) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. <br/>            Read/write **bool**. The default value is **false** . |
| [`slides_layout_options`](/slides/python-net/aspose.slides.export/htmloptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](/slides/python-net/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/aspose.slides.export/htmloptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only [`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/aspose.slides.export/htmloptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is `false`. |
| [`html_formatter`](/slides/python-net/aspose.slides.export/htmloptions/html_formatter/) | Returns or sets HTML template.<br/>            Read/write [`IHtmlFormatter`](/slides/python-net/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/aspose.slides.export/htmloptions/disable_font_ligatures/) | Gets or sets a value indicating whether text is rendered without using ligatures.<br/>            When set to `true`, ligatures will be disabled in the rendered output. By default, this property is set to `false`. |
| [`slide_image_format`](/slides/python-net/aspose.slides.export/htmloptions/slide_image_format/) | Returns or sets slide image format options.<br/>            Read/write [`ISlideImageFormat`](/slides/python-net/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/aspose.slides.export/htmloptions/jpeg_quality/) | Returns or sets a value determining the quality of the JPEG images inside PDF document.<br/>            Read/write **int**. |
| [`pictures_compression`](/slides/python-net/aspose.slides.export/htmloptions/pictures_compression/) | Represents the pictures compression level |
| [`delete_pictures_cropped_areas`](/slides/python-net/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped <br/>            parts will removed, if false they will be serialized in the document (which can possible lead to a <br/>            larger file) |
| [`svg_responsive_layout`](/slides/python-net/aspose.slides.export/htmloptions/svg_responsive_layout/) | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise.<br/>            Read/write **bool**. |


### See Also
* class [`HtmlOptions`](/slides/python-net/aspose.slides.export/htmloptions)
* class [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

