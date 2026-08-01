---
title: get_BwConversionMode()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert het algoritme voor het converteren van een kleurafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als ITiffOptions::get_CompressionType() is ingesteld op TiffCompressionTypes::CCITT4 of TiffCompressionTypes::CCITT3 Lees BlackWhiteConversionMode. Standaard is BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /nl/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() methode


Specificeert het algoritme voor het converteren van een kleurafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) is ingesteld op [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) of [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Lees [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Standaard is [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
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
* Klasse [TiffOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)