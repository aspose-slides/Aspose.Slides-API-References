---
title: get_BwConversionMode()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt den Algorithmus an, der ein Farbbild in ein Schwarz-weiß-Bild konvertiert. Diese Option wird nur angewendet, wenn ITiffOptions::get_CompressionType() auf TiffCompressionTypes::CCITT4 oder TiffCompressionTypes::CCITT3 gesetzt ist. Lesen Sie BlackWhiteConversionMode. Standard ist BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /de/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() Methode

Gibt den Algorithmus an, der ein Farbbild in ein Schwarz-weiß-Bild konvertiert. Diese Option wird nur angewendet, wenn [ITiffOptions::get_CompressionType()](../get_compressiontype/) auf [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) oder [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) gesetzt ist. Lesen Sie [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Standard ist [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## Anmerkungen

Das folgende Beispiel zeigt, wie der Konvertierungsalgorithmus auf Dithering gesetzt wird. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Siehe auch

* Aufzählung [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Klasse [ITiffOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)