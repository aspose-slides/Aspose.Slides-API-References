---
title: get_BwConversionMode()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert het algoritme voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als ITiffOptions::get_CompressionType() is ingesteld op TiffCompressionTypes::CCITT4 of TiffCompressionTypes::CCITT3 Lees BlackWhiteConversionMode. Standaard is BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /nl/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() methode


Specificeert het algoritme voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als [ITiffOptions::get_CompressionType()](../get_compressiontype/) is ingesteld op [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) of [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Lees [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Standaard is [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
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
* Naamruimte [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)