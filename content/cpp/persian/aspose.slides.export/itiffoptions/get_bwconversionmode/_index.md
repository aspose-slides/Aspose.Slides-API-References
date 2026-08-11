---
title: get_BwConversionMode()
second_title: Aspose.Slides برای C++ مرجع API
description: "الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند. این گزینه فقط در صورتی اعمال می‌شود که ITiffOptions::get_CompressionType() برابر TiffCompressionTypes::CCITT4 یا TiffCompressionTypes::CCITT3 باشد. بخوانید BlackWhiteConversionMode. پیش‌فرض BlackWhiteConversionMode::Default است."
type: docs
weight: 183
url: /fa/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() متد

الگوریتم تبدیل تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند. این گزینه تنها در صورتی اعمال می‌شود که [ITiffOptions::get_CompressionType()](../get_compressiontype/) برابر [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) یا [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) باشد. برای جزئیات بیشتر [BlackWhiteConversionMode](../../blackwhiteconversionmode/) را بخوانید. مقدار پیش‌فرض [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) است.

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## توضیحات

مثال زیر نشان می‌دهد چگونه الگوریتم تبدیل به حالت Dithering تنظیم شود. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## موارد مرتبط

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* کلاس [ITiffOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)