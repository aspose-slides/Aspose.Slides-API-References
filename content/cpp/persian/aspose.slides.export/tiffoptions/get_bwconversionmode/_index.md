---
title: get_BwConversionMode()
second_title: Aspose.Slides برای مرجع API C++
description: "الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه‌سفید را مشخص می‌کند. این گزینه تنها در صورتی اعمال می‌شود که ITiffOptions::get_CompressionType() بر روی TiffCompressionTypes::CCITT4 یا TiffCompressionTypes::CCITT3 تنظیم شده باشد خواندن BlackWhiteConversionMode. مقدار پیش‌فرض BlackWhiteConversionMode::Default است."
type: docs
weight: 196
url: /fa/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() متد


الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه‌سفید را مشخص می‌کند. این گزینه فقط در صورتی اعمال می‌شود که [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) بر روی [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) یا [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) تنظیم شده باشد [BlackWhiteConversionMode](../../blackwhiteconversionmode/) را بخوانید. مقدار پیش‌فرض [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) است.

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## توضیحات


مثال زیر نشان می‌دهد که چگونه الگوریتم تبدیل را به Dithering تنظیم کنید. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## موارد مرتبط

* نوع شمارشی [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* کلاس [TiffOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)