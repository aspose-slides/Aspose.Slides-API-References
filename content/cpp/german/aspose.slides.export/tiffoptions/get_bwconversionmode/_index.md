---
title: get_BwConversionMode()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt den Algorithmus an, der ein Farbbild in ein Schwarz-und-Weiß-Bild konvertiert. Diese Option wird nur angewendet, wenn ITiffOptions::get_CompressionType() auf TiffCompressionTypes::CCITT4 oder TiffCompressionTypes::CCITT3 gesetzt ist. Lesen BlackWhiteConversionMode. Standard ist BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /de/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() Methode

Gibt den Algorithmus an, der ein Farbbild in ein Schwarz-und-Weiß-Bild konvertiert. Diese Option wird nur angewendet, wenn [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) auf [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) oder [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) gesetzt ist. Lesen [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Standardwert ist [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## Anmerkungen

Das folgende Beispiel zeigt, wie man den Konvertierungsalgorithmus auf Dithering einstellt. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Siehe auch

* Aufzählung [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Klasse [TiffOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)