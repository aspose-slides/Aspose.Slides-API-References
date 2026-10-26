---
title: set_BwConversionMode()
second_title: Aspose.Slides voor C++ API Referentie
description: "Specificeert het algoritme voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als ITiffOptions::get_CompressionType() is ingesteld op TiffCompressionTypes::CCITT4 of TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Standaard is BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /nl/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) methode

Specificeert het algoritme voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) is ingesteld op [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) of [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Standaard is [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## Opmerkingen

Het volgende voorbeeld laat zien hoe u het conversie-algoritme instelt op Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Zie ook

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Klasse [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)