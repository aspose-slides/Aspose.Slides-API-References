---
title: get_BwConversionMode()
second_title: Aspose.Slides C++ API Referencia
description: "Meghatározza a színes kép fekete-fehér képpé konvertálásának algoritmusát. Ez a beállítás csak akkor lesz alkalmazva, ha az ITiffOptions::get_CompressionType() értéke TiffCompressionTypes::CCITT4 vagy TiffCompressionTypes::CCITT3 Read BlackWhiteConversionMode. Alapértelmezett a BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /hu/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() metódus


Megadja a színes kép fekete-fehér képpé konvertálásának algoritmusát. Ez a beállítás csak akkor kerül alkalmazásra, ha [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) értéke [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) vagy [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Read [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Az alapértelmezett [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
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
* Osztály [TiffOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)