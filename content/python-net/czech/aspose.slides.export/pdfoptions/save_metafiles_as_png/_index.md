---
title: save_metafiles_as_png property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png vlastnost
True pro konverzi všech metafilek použitých v prezentaci na obrázky PNG.
            Čtení/zápis **bool**.

### Poznámky

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

### Definice:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### Viz také
* třída [`PdfOptions`](/slides/python-net/cs/aspose.slides.export/pdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)