---
title: set_CompressionLevel()
second_title: مرجع API Aspose.Slides برای C++
description: "سطح فشاری که هنگام ذخیره‌سازی سند ارائه استفاده می‌شود را مشخص می‌کند. مقدار پیش‌فرض CompressionLevel::Level6 است."
type: docs
weight: 92
url: /fa/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) متد


سطح فشاری که هنگام ذخیره‌سازی سند ارائه استفاده می‌شود را مشخص می‌کند. مقدار پیش‌فرض [CompressionLevel::Level6](../../compressionlevel/) است.

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## ملاحظات


سطوح فشاری بالاتر فایل‌های کوچکتر تولید می‌کنند اما زمان پردازش بیشتری نیاز دارند. نسبت فشرده‌سازی واقعی به محتوای ارائه وابسته است. 

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
* فضای‌نام [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)