---
title: set_BwConversionMode()
second_title: Aspose.Slides برای مرجع API C++
description: "الگوریتمی را که برای تبدیل تصویر رنگی به تصویر سیاه و سفید استفاده می‌شود، مشخص می‌کند. این گزینه تنها زمانی اعمال می‌شود که ITiffOptions::get_CompressionType() بر روی TiffCompressionTypes::CCITT4 یا TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode تنظیم شده باشد. مقدار پیش‌فرض BlackWhiteConversionMode::Default است."
type: docs
weight: 196
url: /fa/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) متد

الگوریتمی را که برای تبدیل تصویر رنگی به تصویر سیاه و سفید استفاده می‌شود، مشخص می‌کند. این گزینه تنها زمانی اعمال می‌شود که [ITiffOptions::get_CompressionType()](../get_compressiontype/) بر روی [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) یا [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) تنظیم شده باشد. مقدار پیش‌فرض [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) است.

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## توضیحات

مثال زیر نشان می‌دهد که چگونه الگوریتم تبدیل را به Dithering تنظیم می‌کنید. 
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
* کتابخانه [Aspose.Slides](../../../)