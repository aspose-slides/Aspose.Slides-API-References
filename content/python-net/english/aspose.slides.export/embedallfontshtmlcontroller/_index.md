---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/embedallfontshtmlcontroller/
---


## EmbedAllFontsHtmlController class

The formatting controller class to use for embedding all presentation fonts in WOFF format.

The EmbedAllFontsHtmlController type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Creates new instance |
| [__init__](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststring) | Creates new instance |

## Methods

| Method | Description |
| :- | :- |
| [write_document_start](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Called to write html document header. Called once per presentation conversion. |
| [write_document_end](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Called to write html document footer. Called once per presentation conversion. |
| [write_slide_start](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Called to write html slide header. Called once per each of slides. |
| [write_slide_end](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Called to write html slide footer. Called once per each of slides. |
| [write_shape_start](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |
| [write_shape_end](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |
| [write_all_fonts](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Write all fonts contained in [`Presentation`](/slides/python-net/aspose.slides/presentation). |
| [write_font](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-string-string-bytes) | Writes data as base64 into HTML document itself |

