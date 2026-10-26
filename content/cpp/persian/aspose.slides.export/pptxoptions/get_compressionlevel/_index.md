---
title: get_CompressionLevel()
second_title: مرجع API Aspose.Slides برای C++
description: "سطح فشرده‌سازی مورد استفاده هنگام ذخیره‌سازی سند ارائه را مشخص می‌کند. مقدار پیش‌فرض CompressionLevel::Level6 است."
type: docs
weight: 79
url: /fa/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() متد

سطح فشرده‌سازی مورد استفاده هنگام ذخیره‌سازی سند ارائه را مشخص می‌کند. مقدار پیش‌فرض [CompressionLevel::Level6](../../compressionlevel/) است.

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## توضیحات

سطوح فشرده‌سازی بالاتر فایل‌های کوچکتری تولید می‌کند اما زمان پردازش بیشتری نیاز دارد. نسبت فشرده‌سازی واقعی به محتوای ارائه وابسته است.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## موارد مرتبط

* Enum [CompressionLevel](../../compressionlevel/)
* کلاس [PptxOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)