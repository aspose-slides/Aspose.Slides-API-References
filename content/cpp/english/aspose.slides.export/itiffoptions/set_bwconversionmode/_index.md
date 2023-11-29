---
title: set_BwConversionMode()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies the algorithm for converting a color image into a black and white image. This option will applied only if ITiffOptions::get_CompressionType() is set to TiffCompressionTypes::CCITT4 or TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Default is BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) method


Specifies the algorithm for converting a color image into a black and white image. This option will applied only if [ITiffOptions::get_CompressionType()](../get_compressiontype/) is set to [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) or [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Default is [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## Remarks


The following example shows how to set conversion algorithm to Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## See Also

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)