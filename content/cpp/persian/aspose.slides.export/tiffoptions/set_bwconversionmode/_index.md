---
title: set_BwConversionMode()
second_title: مرجع API Aspose.Slides برای C++
description: "الگوریتم تبدیل تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند. این گزینه فقط زمانی اعمال می‌شود که ITiffOptions::get_CompressionType() روی TiffCompressionTypes::CCITT4 یا TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode تنظیم شده باشد. مقدار پیش‌فرض BlackWhiteConversionMode::Default است."
type: docs
weight: 209
url: /fa/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) متد

الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند. این گزینه فقط زمانی اعمال می‌شود که [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) روی [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) یا [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) نوشتن [BlackWhiteConversionMode](../../blackwhiteconversionmode/) تنظیم شده باشد. مقدار پیش‌فرض [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) است.

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## توضیحات

مثال زیر نشان می‌دهد چگونه الگوریتم تبدیل را به Dithering تنظیم کنیم. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## مراجع

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* کلاس [TiffOptions](../)
* فضا نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)