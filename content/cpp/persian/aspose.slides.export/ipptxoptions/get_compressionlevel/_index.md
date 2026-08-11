---
title: get_CompressionLevel()
second_title: Aspose.Slides برای C++ مرجع API
description: "سطح فشرده‌سازی که هنگام ذخیره‌سازی سند ارائه استفاده می‌شود را مشخص می‌کند. مقدار پیش‌فرض CompressionLevel::Level6 است."
type: docs
weight: 79
url: /fa/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() متد

سطح فشرده‌سازی که هنگام ذخیره‌سازی سند ارائه استفاده می‌شود را مشخص می‌کند. مقدار پیش‌فرض [CompressionLevel::Level6](../../compressionlevel/) است.

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## توضیحات

سطوح فشرده‌سازی بالاتر فایل‌های کوچکتری تولید می‌کنند اما زمان پردازش بیشتری نیاز دارند. نسبت فشرده‌سازی واقعی به محتوای ارائه بستگی دارد.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## موارد مرتبط

* شمارش [CompressionLevel](../../compressionlevel/)
* کلاس [IPptxOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)