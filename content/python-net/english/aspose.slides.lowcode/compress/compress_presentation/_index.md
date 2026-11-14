---
title: compress_presentation method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---


## compress_presentation(presentation) {#presentation}
Reduces the size of a presentation by applying all available compression steps:
            
* Removes unused master slides **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Removes unused layout slides **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Keeps only the glyphs actually used in embedded fonts **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Reduces picture resolution to 150 DPI and deletes cropped areas of pictures **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/aspose.slides/presentation) | The presentation to compress. |

### Remarks

To customize compression, for example to use a different picture resolution or to skip a step,
            call the methods listed above individually instead of this one.
            Cropped areas of pictures are removed permanently and cannot be restored in PowerPoint.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` is `None`. |



### See Also
* class [`Compress`](/slides/python-net/aspose.slides.lowcode/compress)
* class [`Presentation`](/slides/python-net/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)

