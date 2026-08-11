---
title: get_BwConversionMode()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود. سيُطبق هذا الخيار فقط إذا تم تعيين ITiffOptions::get_CompressionType() إلى TiffCompressionTypes::CCITT4 أو TiffCompressionTypes::CCITT3 Read BlackWhiteConversionMode. القيمة الافتراضية هي BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /ar/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() طريقة

يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود. سيُطبق هذا الخيار فقط إذا تم تعيين [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) إلى [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) أو [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) اقرأ [BlackWhiteConversionMode](../../blackwhiteconversionmode/). القيمة الافتراضية هي [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## ملاحظات

المثال التالي يوضح كيفية ضبط خوارزمية التحويل إلى Dithering.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## انظر أيضًا

* تعداد [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* فئة [TiffOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)