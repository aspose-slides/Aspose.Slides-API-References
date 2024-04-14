---
title: IHtmlFormattingController class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/ihtmlformattingcontroller/
---


## IHtmlFormattingController class

Controls a html file generation.

The IHtmlFormattingController type exposes the following members:

## Methods

| Method | Description |
| :- | :- |
| [write_document_start](/slides/python-net/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Called to write html document header. Called once per presentation conversion. |
| [write_document_end](/slides/python-net/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Called to write html document footer. Called once per presentation conversion. |
| [write_slide_start](/slides/python-net/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Called to write html slide header. Called once per each of slides. |
| [write_slide_end](/slides/python-net/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Called to write html slide footer. Called once per each of slides. |
| [write_shape_start](/slides/python-net/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |
| [write_shape_end](/slides/python-net/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

