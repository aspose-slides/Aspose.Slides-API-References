---
title: IPdfOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/
---


## IPdfOptions class

Provides options that control how a presentation is saved in Pdf format.

The IPdfOptions type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [text_compression](/slides/python-net/aspose.slides.export/text_compression) | Specifies compression type to be used for all textual content in the document.<br/>            Read/write :py:enum:`aspose.slides.export.PdfTextCompression`. |
| [best_images_compression_ratio](/slides/python-net/aspose.slides.export/best_images_compression_ratio) | Indicates if the most effective compression (instead of the default one) for each image must be selected <br/>            automatically. If set to :py:class:`bool`.true, for every image in presentation the most appropriate compression <br/>            algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. |
| [embed_true_type_fonts_for_ascii](/slides/python-net/aspose.slides.export/embed_true_type_fonts_for_ascii) | True to embed true type fonts for ASCII characters 32-127.<br/>            Fonts for character codes greater than 127 are always embedded.<br/>            Read/write :py:class:`bool`. |
| [show_hidden_slides](/slides/python-net/aspose.slides.export/show_hidden_slides) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is ``false``. |
| [additional_common_font_families](/slides/python-net/aspose.slides.export/additional_common_font_families) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common.<br/>            Read/write :py:class:`System.String`[]. |
| [embed_full_fonts](/slides/python-net/aspose.slides.export/embed_full_fonts) | Determines if all characters of font should be embedded or only used subset.<br/>            Read/write :py:class:`bool`. |
| [jpeg_quality](/slides/python-net/aspose.slides.export/jpeg_quality) | Returns or sets a value determining the quality of the JPEG images inside PDF document.<br/>            Read/write :py:class:`int`. |
| [compliance](/slides/python-net/aspose.slides.export/compliance) | Desired conformance level for generated PDF document.<br/>            Read/write :py:enum:`aspose.slides.export.PdfCompliance`. |
| [password](/slides/python-net/aspose.slides.export/password) | Setting user password to protect the PDF document. <br/>            Read/write :py:class:`System.String`. |
| [access_permissions](/slides/python-net/aspose.slides.export/access_permissions) | Contains a set of flags specifying which access permissions should be granted when the document is opened<br/>            with user access. See :py:enum:`aspose.slides.export.PdfAccessPermissions`. |
| [save_metafiles_as_png](/slides/python-net/aspose.slides.export/save_metafiles_as_png) | True to convert all metafiles used in a presentation to the PNG images.<br/>            Read/write :py:class:`bool`. |
| [sufficient_resolution](/slides/python-net/aspose.slides.export/sufficient_resolution) | Returns or sets a value determining resolution of images inside PDF document.<br/>            <br/>            Read/write :py:class:`float`. |
| [draw_slides_frame](/slides/python-net/aspose.slides.export/draw_slides_frame) | True to draw black frame around each slide.<br/>             Read/write :py:class:`bool`. |
| [notes_comments_layouting](/slides/python-net/aspose.slides.export/notes_comments_layouting) | Provides options that control how notes and comments is placed in exported document. |
| [slides_layout_options](/slides/python-net/aspose.slides.export/slides_layout_options) | Gets or sets the mode in which slides are placed on the page when exporting a presentation :py:class:`aspose.slides.export.ISlidesLayoutOptions`. |
| [image_transparent_color](/slides/python-net/aspose.slides.export/image_transparent_color) | Gets or sets the image transparent color. |
| [apply_image_transparent](/slides/python-net/aspose.slides.export/apply_image_transparent) | Applies the specified transparent color to an image if ``true``. |
| [ink_options](/slides/python-net/aspose.slides.export/ink_options) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only :py:class:`aspose.slides.export.IInkOptions` |
| [as_i_save_options](/slides/python-net/aspose.slides.export/as_i_save_options) | Returns ISaveOptions interface.<br/>            Read-only :py:class:`aspose.slides.export.ISaveOptions`. |
| [warning_callback](/slides/python-net/aspose.slides.export/warning_callback) |  |
| [progress_callback](/slides/python-net/aspose.slides.export/progress_callback) |  |
| [default_regular_font](/slides/python-net/aspose.slides.export/default_regular_font) |  |

