---
title: get_BwConversionMode()
second_title: Aspose.Slides C++ API hivatkozás
description: "Megadja a színes kép fekete-fehér képpé konvertálásához használt algoritmust. Ez az opció csak akkor lesz alkalmazva, ha ITiffOptions::get_CompressionType() TiffCompressionTypes::CCITT4 vagy TiffCompressionTypes::CCITT3 értékre van állítva. Olvassa el BlackWhiteConversionMode. Alapértelmezett a BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /hu/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() metódus

Megadja a színes kép fekete-fehér képpé konvertálásához használt algoritmust. Ez a beállítás csak akkor kerül alkalmazásra, ha [ITiffOptions::get_CompressionType()](../get_compressiontype/) [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) vagy [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) értékre van állítva. Olvassa el [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Alapértelmezett: [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## Megjegyzés

Az alábbi példa mutatja, hogyan állítható be a konverziós algoritmus Dithering.
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