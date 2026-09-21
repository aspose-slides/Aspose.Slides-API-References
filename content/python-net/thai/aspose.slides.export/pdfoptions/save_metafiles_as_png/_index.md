---
title: save_metafiles_as_png property
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png คุณสมบัติ
True to convert all metafiles used in a presentation to the PNG images.
            Read/write **bool**.

### หมายเหตุ

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

### คำนิยาม:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`PdfOptions`](/slides/python-net/th/aspose.slides.export/pdfoptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)