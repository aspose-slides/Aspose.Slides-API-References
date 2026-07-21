---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides для C++ справочник API
description: True, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Write bool.
type: docs
weight: 300
url: /ru/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) method


True, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Write **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Примечания


Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible. 
## См. также

* Class [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)