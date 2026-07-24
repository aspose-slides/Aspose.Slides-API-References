---
title: set_BwConversionMode()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt den Algorithmus für die Umwandlung eines Farbbildes in ein Schwarz-Weiß-Bild an. Diese Option wird nur angewendet, wenn ITiffOptions::get_CompressionType() auf TiffCompressionTypes::CCITT4 oder TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode gesetzt ist. Standard ist BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /de/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) Methode

Gibt den Algorithmus zum Umwandeln eines Farbbildes in ein Schwarz-Weiß-Bild an. Diese Option wird nur angewendet, wenn [ITiffOptions::get_CompressionType()](../get_compressiontype/) auf [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) oder [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) gesetzt ist. Standard ist [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## Hinweise

Das folgende Beispiel zeigt, wie der Umwandlungsalgorithmus auf Dithering gesetzt wird.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Siehe auch

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Klasse [ITiffOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)