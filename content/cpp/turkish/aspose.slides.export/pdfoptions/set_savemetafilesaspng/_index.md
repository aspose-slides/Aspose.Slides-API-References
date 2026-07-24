---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için True. bool yazın.
type: docs
weight: 339
url: /tr/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) metodu

True to convert all metafiles used in a presentation to the PNG images. Write **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Açıklamalar

Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

## İlgili

* Sınıf [PdfOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)