﻿---
title: PdfOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/pdfoptions/
---


## PdfOptions class

Provides options that control how a presentation is saved in Pdf format.

**Inheritance:**[`PdfOptions`](/slides/python-net/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The PdfOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.export/pdfoptions/__init__/#) | Default constructor. |

## Properties

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/aspose.slides.export/pdfoptions/warning_callback/) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/aspose.slides.export/pdfoptions/progress_callback/) | Represents a callback object for saving progress updates in percentage.<br/>            See [`IProgressCallback`](/slides/python-net/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/aspose.slides.export/pdfoptions/default_regular_font/) | Returns or sets font used in case source font is not found.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/aspose.slides.export/pdfoptions/gradient_style/) | Returns or sets the visual style of the gradient.<br/>            Read/write [`GradientStyle`](/slides/python-net/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/aspose.slides.export/pdfoptions/skip_java_script_links/) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. <br/>            Read/write **bool**. The default value is **false** . |
| [`slides_layout_options`](/slides/python-net/aspose.slides.export/pdfoptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](/slides/python-net/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/aspose.slides.export/pdfoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only [`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/aspose.slides.export/pdfoptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is `false`. |
| [`text_compression`](/slides/python-net/aspose.slides.export/pdfoptions/text_compression/) | Specifies compression type to be used for all textual content in the document.<br/>            Read/write [`PdfTextCompression`](/slides/python-net/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Indicates if the most effective compression (instead of the default one) for each image must be selected <br/>            automatically. If set to **bool**.true, for every image in presentation the most appropriate compression <br/>            algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. <br/>Best image compression ratio selection is computationally expensive and takes <br/>            an additional amount of RAM, and this option is **bool**.false by default. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text.<br/>            Fonts for character codes greater than 127 are always embedded.<br/>            Common fonts list includes PDF's base 14 fonts and additional user specified fonts.<br/>            Read/write **bool**. |
| [`additional_common_font_families`](/slides/python-net/aspose.slides.export/pdfoptions/additional_common_font_families/) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common.<br/>            Read/write **str**[]. |
| [`embed_full_fonts`](/slides/python-net/aspose.slides.export/pdfoptions/embed_full_fonts/) | Determines if all characters of font should be embedded or only used subset.<br/>            Read/write **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling.<br/>            This approach can enhance the quality of text in the resulting PDF for certain fonts.<br/>            Read/write **bool**. |
| [`jpeg_quality`](/slides/python-net/aspose.slides.export/pdfoptions/jpeg_quality/) | Returns or sets a value determining the quality of the JPEG images inside PDF document.<br/>            Read/write **int**. |
| [`compliance`](/slides/python-net/aspose.slides.export/pdfoptions/compliance/) | Desired conformance level for generated PDF document.<br/>            Read/write [`PdfCompliance`](/slides/python-net/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/aspose.slides.export/pdfoptions/password/) | Setting user password to protect the PDF document. <br/>            Read/write **str**. |
| [`access_permissions`](/slides/python-net/aspose.slides.export/pdfoptions/access_permissions/) | Contains a set of flags specifying which access permissions should be granted when the document is opened<br/>            with user access. See [`PdfAccessPermissions`](/slides/python-net/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | True to convert all metafiles used in a presentation to the PNG images.<br/>            Read/write **bool**. |
| [`sufficient_resolution`](/slides/python-net/aspose.slides.export/pdfoptions/sufficient_resolution/) | Returns or sets a value determining resolution of images inside PDF document.<br/><br/>Property affects on file size, time of export and image quality.<br/><br/><br/>The default value is **96** .<br/><br/><br/>            Read/write **float**. |
| [`draw_slides_frame`](/slides/python-net/aspose.slides.export/pdfoptions/draw_slides_frame/) | True to draw black frame around each slide.<br/>             Read/write **bool**. |
| [`image_transparent_color`](/slides/python-net/aspose.slides.export/pdfoptions/image_transparent_color/) | Gets or sets the image transparent color. |
| [`apply_image_transparent`](/slides/python-net/aspose.slides.export/pdfoptions/apply_image_transparent/) | Applies the specified transparent color to an image if `true`. |
| [`include_ole_data`](/slides/python-net/aspose.slides.export/pdfoptions/include_ole_data/) | True to convert all OLE data from the presentation to embedded files in the resulting PDF.<br/>            Read/write **bool**. |


### Examples

The following example shows how to convert PowerPoint to PDF with custom options.

            The following example shows how to convert PowerPoint to PDF with hidden slides.

            The following example shows how to convert PowerPoint to password protected PDF.

            The following example shows how to convert PowerPoint to PDF with notes.


### See Also
* class [`PdfOptions`](/slides/python-net/aspose.slides.export/pdfoptions)
* class [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

