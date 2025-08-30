---
title: IHtmlOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/ihtmloptions/
---


## IHtmlOptions class

Represents a HTML exporting options.

The IHtmlOptions type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`html_formatter`](/slides/python-net/aspose.slides.export/ihtmloptions/html_formatter/) | Returns or sets HTML template.<br/>            Read/write [`IHtmlFormatter`](/slides/python-net/aspose.slides.export/ihtmlformatter). |
| [`slide_image_format`](/slides/python-net/aspose.slides.export/ihtmloptions/slide_image_format/) | Returns or sets slide image format options.<br/>            Read/write [`ISlideImageFormat`](/slides/python-net/aspose.slides.export/islideimageformat). |
| [`show_hidden_slides`](/slides/python-net/aspose.slides.export/ihtmloptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is `false`. |
| [`jpeg_quality`](/slides/python-net/aspose.slides.export/ihtmloptions/jpeg_quality/) | Returns or sets a value determining the quality of the JPEG images inside PDF document.<br/>            Read/write **int**. |
| [`pictures_compression`](/slides/python-net/aspose.slides.export/ihtmloptions/pictures_compression/) | Represents the pictures compression level<br/>            Read/write [`IHtmlOptions.pictures_compression`](/slides/python-net/aspose.slides.export/ihtmloptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/aspose.slides.export/ihtmloptions/delete_pictures_cropped_areas/) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped <br/>            parts will removed, if false they will be serialized in the document (which can possible lead to a <br/>            larger file)<br/>            Read/write **bool**. |
| [`svg_responsive_layout`](/slides/python-net/aspose.slides.export/ihtmloptions/svg_responsive_layout/) | True to exclude width and height attributes from SVG container - that will make layout responsive. False - otherwise.<br/>            Read/write **bool**. |
| [`disable_font_ligatures`](/slides/python-net/aspose.slides.export/ihtmloptions/disable_font_ligatures/) | Gets or sets a value indicating whether text is rendered without using ligatures.<br/>            When set to `true`, ligatures will be disabled in the rendered output. By default, this property is set to `false`. |
| [`slides_layout_options`](/slides/python-net/aspose.slides.export/ihtmloptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](/slides/python-net/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/aspose.slides.export/ihtmloptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only [`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |


### See Also
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

