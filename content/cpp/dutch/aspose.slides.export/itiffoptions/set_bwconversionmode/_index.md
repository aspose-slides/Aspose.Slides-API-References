---
title: set_BwConversionMode()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert het algoritme voor het converteren van een kleurbeeld naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als ITiffOptions::get_CompressionType() is ingesteld op TiffCompressionTypes::CCITT4 of TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Standaard is BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /nl/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) methode

Specifieert het algoritme voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als [ITiffOptions::get_CompressionType()](../get_compressiontype/) is ingesteld op [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) of [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Standaard is [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## Opmerkingen

Het volgende voorbeeld toont hoe het conversie-algoritme in te stellen op Dithering.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Zie ook

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Klasse [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)