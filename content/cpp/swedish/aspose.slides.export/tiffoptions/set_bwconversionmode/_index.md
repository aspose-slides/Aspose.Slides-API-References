---
title: set_BwConversionMode()
second_title: Aspose.Slides för C++ API-referens
description: "Specificerar algoritmen för att konvertera en färgbild till en svartvit bild. Detta alternativ kommer endast att tillämpas om ITiffOptions::get_CompressionType() är inställt på TiffCompressionTypes::CCITT4 eller TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Standard är BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /sv/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metod


Specificerar algoritmen för att konvertera en färgbild till en svartvit bild. Detta alternativ kommer endast att tillämpas om [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) är inställt på [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) eller [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Standard är [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
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

## Se också

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)