---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API Reference
description: True to convert all metafiles used in a presentation to the PNG images. Read bool.
type: docs
weight: 339
url: /aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() method


True to convert all metafiles used in a presentation to the PNG images. Read **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Remarks


Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible. 
## See Also

* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)