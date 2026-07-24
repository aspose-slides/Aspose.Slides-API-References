---
title: set_BwConversionMode()
second_title: Aspose.Slides für C++ API-Referenz
description: "Legt den Algorithmus fest, mit dem ein Farbbild in ein Schwarz-und-Weiß-Bild konvertiert wird. Diese Option wird nur angewendet, wenn ITiffOptions::get_CompressionType() auf TiffCompressionTypes::CCITT4 oder TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode gesetzt ist. Standard ist BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /de/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) Methode

Gibt den Algorithmus an, der ein Farbbild in ein Schwarz-und-Weiß-Bild konvertiert. Diese Option wird nur angewendet, wenn [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) auf [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) oder [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) gesetzt ist. Standard ist [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## Bemerkungen

Das folgende Beispiel zeigt, wie der Konversionsalgorithmus auf Dithering gesetzt wird.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Siehe auch

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)