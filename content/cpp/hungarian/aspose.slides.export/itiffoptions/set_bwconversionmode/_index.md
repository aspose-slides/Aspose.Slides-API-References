---
title: set_BwConversionMode()
second_title: Aspose.Slides for C++ API referenciája
description: "Meghatározza egy színes kép fekete-fehér képpé konvertálásának algoritmusát. Ez az opció csak akkor lesz alkalmazva, ha az ITiffOptions::get_CompressionType() TiffCompressionTypes::CCITT4 vagy TiffCompressionTypes::CCITT3 értékre van beállítva. Írja BlackWhiteConversionMode. Az alapértelmezett érték BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /hu/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metódus

Megadja a színes kép fekete-fehér képpé konvertálásának algoritmusát. Ez az opció csak akkor lesz alkalmazva, ha a [ITiffOptions::get_CompressionType()](../get_compressiontype/) [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) vagy [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) értékre van beállítva. Írja [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Az alapértelmezett érték [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## Megjegyzések

Az alábbi példa bemutatja, hogyan állítható be a konverziós algoritmus Dithering-re. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Lásd még

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Osztály [ITiffOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)