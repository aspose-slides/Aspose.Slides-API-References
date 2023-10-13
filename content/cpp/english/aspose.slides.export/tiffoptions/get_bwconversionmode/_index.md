---
title: get_BwConversionMode()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies the algorithm for converting a color image into a black and white image. This option will applied only if CompressionType is set to TiffCompressionTypes::CCITT4 or TiffCompressionTypes::CCITT3 Read BlackWhiteConversionMode. Default is BlackWhiteConversionMode::Default."
type: docs
weight: 170
url: /aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() method


Specifies the algorithm for converting a color image into a black and white image. This option will applied only if [CompressionType](../) is set to [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) or [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Read [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Default is [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## Remarks



```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## See Also

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)