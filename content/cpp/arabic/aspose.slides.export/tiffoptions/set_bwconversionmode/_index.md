---
title: set_BwConversionMode()
second_title: مرجع Aspose.Slides لـ C++
description: "يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود. يتم تطبيق هذا الخيار فقط إذا تم تعيين ITiffOptions::get_CompressionType() إلى TiffCompressionTypes::CCITT4 أو TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. القيمة الافتراضية هي BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /ar/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) طريقة

يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود. سيتم تطبيق هذا الخيار فقط إذا تم تعيين [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) إلى [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) أو [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). القيمة الافتراضية هي [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## ملاحظات

يوضح المثال التالي كيفية ضبط خوارزمية التحويل إلى Dithering.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## انظر أيضًا

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* فئة [TiffOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)