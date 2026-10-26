---
title: set_BwConversionMode()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود. سيُطبق هذا الخيار فقط إذا تم تعيين ITiffOptions::get_CompressionType() إلى TiffCompressionTypes::CCITT4 أو TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. القيمة الافتراضية هي BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /ar/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) طريقة

يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود. سيُطبق هذا الخيار فقط إذا تم تعيين [ITiffOptions::get_CompressionType()](../get_compressiontype/) إلى [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) أو [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). القيمة الافتراضية هي [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## ملاحظات

يوضح المثال التالي كيفية تعيين خوارزمية التحويل إلى Dithering.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## انظر أيضا

* تعداد [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* فئة [ITiffOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)