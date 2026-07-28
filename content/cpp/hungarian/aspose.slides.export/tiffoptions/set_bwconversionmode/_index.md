---
title: set_BwConversionMode()
second_title: Aspose.Slides C++ API referencia
description: "Megadja a színes képet fekete-fehér képpé konvertáló algoritmust. Ez a beállítás csak akkor lesz alkalmazva, ha ITiffOptions::get_CompressionType() TiffCompressionTypes::CCITT4 vagy TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode értékre van állítva. Alapértelmezett a BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /hu/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metódus

Megadja a színes képet fekete-fehér képpé konvertáló algoritmust. Ez a beállítás csak akkor lesz alkalmazva, ha [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) vagy [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) írásra van állítva [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Alapértelmezett érték [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## Megjegyzések

Az alábbi példa bemutatja, hogyan kell a konverziós algoritmust Dithering-re állítani.
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
* Névterület [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)