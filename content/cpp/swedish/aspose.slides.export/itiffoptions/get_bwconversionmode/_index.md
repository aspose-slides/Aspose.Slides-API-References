---
title: get_BwConversionMode()
second_title: Aspose.Slides för C++ API-referens
description: "Anger algoritmen för att konvertera en färgbild till en svartvit bild. Detta alternativ tillämpas endast om ITiffOptions::get_CompressionType() är inställd på TiffCompressionTypes::CCITT4 eller TiffCompressionTypes::CCITT3 Läs BlackWhiteConversionMode. Standard är BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /sv/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() metod

Anger algoritmen för att konvertera en färgbild till en svartvitt bild. Detta alternativ kommer att tillämpas endast om [ITiffOptions::get_CompressionType()](../get_compressiontype/) är inställd på [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) eller [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Läs [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Standard är [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
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
* Klass [ITiffOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)