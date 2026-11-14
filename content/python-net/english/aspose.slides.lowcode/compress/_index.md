---
title: Compress class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.lowcode/compress/
---


## Compress class

Represents a group of methods intended to compress [`Presentation`](/slides/python-net/aspose.slides/presentation).

The Compress type exposes the following members:

## Methods

| Method | Description |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Reduces the size of a presentation by applying all available compression steps:<br/>            <br/>* Removes unused master slides **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Removes unused layout slides **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Keeps only the glyphs actually used in embedded fonts **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Reduces picture resolution to 150 DPI and deletes cropped areas of pictures **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Makes compression of the [`Presentation`](/slides/python-net/aspose.slides/presentation) by removing unused master slides. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Makes compression of the [`Presentation`](/slides/python-net/aspose.slides/presentation) by removing unused layout slides. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Makes compression of the [`Presentation`](/slides/python-net/aspose.slides/presentation) by removing unused characters from embedded fonts. |
| [`compress_images(presentation, resolution)`](/slides/python-net/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Reduces the resolution of pictures in the presentation and deletes their cropped areas,<br/>            similar to PowerPoint's "Compress Pictures" applied to all pictures.<br/>            Pictures on slides, layout slides and master slides are processed, including pictures inside group shapes<br/>            and picture fills of shapes. |


### See Also
* class [`Presentation`](/slides/python-net/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)

