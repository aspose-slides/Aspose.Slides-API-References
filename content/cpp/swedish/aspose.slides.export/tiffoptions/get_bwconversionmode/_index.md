---
title: get_BwConversionMode()
second_title: Aspose.Slides för C++ API-referens
description: "Anger algoritmen för att konvertera en färgbild till en svart-vit bild. Detta alternativ tillämpas endast om ITiffOptions::get_CompressionType() är inställd på TiffCompressionTypes::CCITT4 eller TiffCompressionTypes::CCITT3 Läs BlackWhiteConversionMode. Standard är BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /sv/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() metod


Anger algoritmen för att konvertera en färgbild till en svart-vit bild. Detta alternativ tillämpas endast om [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) är inställd på [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) eller [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/). Läs [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Standard är [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## Anmärkningar


Följande exempel visar hur man ställer in konverteringsalgoritmen till Dithering.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Se även

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Klass [TiffOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)