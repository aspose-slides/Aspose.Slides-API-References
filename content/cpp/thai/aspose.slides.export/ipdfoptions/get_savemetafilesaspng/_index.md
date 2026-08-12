---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: True เพื่อแปลง metafile ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน bool.
type: docs
weight: 287
url: /th/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() เมธอด

True เพื่อแปลง metafile ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## หมายเหตุ

Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

## ดูเพิ่มเติม

* คลาส [IPdfOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)