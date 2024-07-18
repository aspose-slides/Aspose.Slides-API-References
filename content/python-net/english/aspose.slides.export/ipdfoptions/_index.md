---
title: IPdfOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/ipdfoptions/
---


## IPdfOptions class

Provides options that control how a presentation is saved in Pdf format.

The IPdfOptions type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/aspose.slides.export/ipdfoptions/text_compression/) | Specifies compression type to be used for all textual content in the document.<br/>            Read/write [`PdfTextCompression`](/slides/python-net/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Indicates if the most effective compression (instead of the default one) for each image must be selected <br/>            automatically. If set to **bool**.true, for every image in presentation the most appropriate compression <br/>            algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. <br/>            Best image compression ratio selection is computationally expensive and takes <br/>            an additional amount of RAM, and this option is **bool**.false by default. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | True to embed true type fonts for ASCII characters 32-127.<br/>            Fonts for character codes greater than 127 are always embedded.<br/>            Read/write **bool**. |
| [`show_hidden_slides`](/slides/python-net/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is `false`. |
| [`additional_common_font_families`](/slides/python-net/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common.<br/>            Read/write **str**[]. |
| [`embed_full_fonts`](/slides/python-net/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Determines if all characters of font should be embedded or only used subset.<br/>            Read/write **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling.<br/>            This approach can enhance the quality of text in the resulting PDF for certain fonts.<br/>            Read/write **bool**. |
| [`jpeg_quality`](/slides/python-net/aspose.slides.export/ipdfoptions/jpeg_quality/) | Returns or sets a value determining the quality of the JPEG images inside PDF document.<br/>            Read/write **int**. |
| [`compliance`](/slides/python-net/aspose.slides.export/ipdfoptions/compliance/) | Desired conformance level for generated PDF document.<br/>            Read/write [`PdfCompliance`](/slides/python-net/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/aspose.slides.export/ipdfoptions/password/) | Setting user password to protect the PDF document. <br/>            Read/write **str**. |
| [`access_permissions`](/slides/python-net/aspose.slides.export/ipdfoptions/access_permissions/) | Contains a set of flags specifying which access permissions should be granted when the document is opened<br/>            with user access. See [`PdfAccessPermissions`](/slides/python-net/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | True to convert all metafiles used in a presentation to the PNG images.<br/>            Read/write **bool**. |
| [`sufficient_resolution`](/slides/python-net/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Returns or sets a value determining resolution of images inside PDF document.<br/>            <br/>Property affects on file size, time of export and image quality.<br/><br/><br/>The default value is **96** .<br/><br/><br/>            Read/write **float**. |
| [`draw_slides_frame`](/slides/python-net/aspose.slides.export/ipdfoptions/draw_slides_frame/) | True to draw black frame around each slide.<br/>             Read/write **bool**. |
| [`notes_comments_layouting`](/slides/python-net/aspose.slides.export/ipdfoptions/notes_comments_layouting/) | Provides options that control how notes and comments is placed in exported document. |
| [`slides_layout_options`](/slides/python-net/aspose.slides.export/ipdfoptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](/slides/python-net/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/aspose.slides.export/ipdfoptions/image_transparent_color/) | Gets or sets the image transparent color. |
| [`apply_image_transparent`](/slides/python-net/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Applies the specified transparent color to an image if `true`. |
| [`ink_options`](/slides/python-net/aspose.slides.export/ipdfoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only [`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/aspose.slides.export/ipdfoptions/include_ole_data/) | True to convert all OLE data from the presentation to embedded files in the resulting PDF.<br/>            Read/write **bool**. |
| [`warning_callback`](/slides/python-net/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/aspose.slides.export/ipdfoptions/gradient_style/) |  |


### See Also
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

