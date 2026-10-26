---
title: set_BwConversionMode()
second_title: Aspose.Slides för C++ API-referens
description: "Specificerar algoritmen för att konvertera en färgbild till en svartvit bild. Detta alternativ kommer endast att tillämpas om ITiffOptions::get_CompressionType() är inställd på TiffCompressionTypes::CCITT4 eller TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Standard är BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /sv/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metod

Specificerar algoritmen för att konvertera en färgbild till en svartvit bild. Detta alternativ kommer att tillämpas endast om [ITiffOptions::get_CompressionType()](../get_compressiontype/) är inställd på [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) eller [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Standard är [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
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