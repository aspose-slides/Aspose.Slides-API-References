---
title: compress_images method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.lowcode/compress/compress_images/
weight: 20
---


## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Reduces the resolution of pictures in the presentation and deletes their cropped areas,
            similar to PowerPoint's "Compress Pictures" applied to all pictures.
            Pictures on slides, layout slides and master slides are processed, including pictures inside group shapes
            and picture fills of shapes.


```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) | The presentation to process. |
| resolution | [`PicturesCompression`](/slides/python-net/aspose.slides.export/picturescompression) | Target resolution relative to the size at which each picture is displayed.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) leaves pictures unchanged. |

### Remarks

Pictures already at or below the target resolution are left unchanged; pictures are never upscaled.


Not processed: slide backgrounds, table cell fills, charts, SmartArt, GIF images (to preserve animation),
            SVG and metafile (EMF/WMF) images.


Cropped areas are removed permanently and cannot be restored in PowerPoint.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` is `None`. |



### See Also
* class [`Compress`](/slides/python-net/aspose.slides.lowcode/compress)
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* enumeration [`PicturesCompression`](/slides/python-net/aspose.slides.export/picturescompression)
* module [`aspose.slides.lowcode`](/slides/python-net/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)

