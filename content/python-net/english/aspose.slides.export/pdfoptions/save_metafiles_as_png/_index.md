---
title: save_metafiles_as_png property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 180
---


## save_metafiles_as_png property
True to convert all metafiles used in a presentation to the PNG images.
            Read/write .NET type System.Boolean.


### Remarks

Default is **true** .
            Pdf document can contain vector graphics and raster images. 
            If SaveMetafilesAsPng is set to true then source Metafile 
            image is converted to Png format and saved to Pdf as a raster 
            image. If SaveMetafilesAsPng is set to false then source Metafile 
            is converted to Pdf vector graphics. Each approach has advantages 
            and disadvantages. For example, if Metafile is converted to PNG, 
            then some quality loss is possible during resulting 
            document scaling. If Metafile is converted to Pdf vector graphics, 
            then performance issues in Pdf viewing tool are possible.

### Definition:
```python
@property
def save_metafiles_as_png(self):
    ...
@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```
