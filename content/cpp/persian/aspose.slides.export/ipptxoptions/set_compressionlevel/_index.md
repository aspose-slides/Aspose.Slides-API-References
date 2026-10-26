---
title: set_CompressionLevel()
second_title: مرجع API Aspose.Slides برای C++
description: "سطح فشرده‌سازی که هنگام ذخیره‌سازی سند ارائه استفاده می‌شود را مشخص می‌کند. مقدار پیش‌فرض CompressionLevel::Level6 است."
type: docs
weight: 92
url: /fa/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) متد

سطح فشرده‌سازی که هنگام ذخیره‌سازی سند ارائه استفاده می‌شود را مشخص می‌کند. مقدار پیش‌فرض [CompressionLevel::Level6](../../compressionlevel/) است.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## توضیحات

سطوح بالاتر فشرده‌سازی فایل‌های کوچکتر تولید می‌کنند اما زمان پردازش بیشتری نیاز دارند. نسبت فشرده‌سازی واقعی به محتوای ارائه بستگی دارد.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## موارد مرتبط

* Enum [CompressionLevel](../../compressionlevel/)
* کلاس [IPptxOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)