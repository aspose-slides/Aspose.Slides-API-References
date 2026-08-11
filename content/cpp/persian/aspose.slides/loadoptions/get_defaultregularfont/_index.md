---
title: get_DefaultRegularFont()
second_title: مرجع API Aspose.Slides برای C++
description: "فونت Regular را برمی‌گرداند که در صورت عدم یافتن فونت منبع استفاده می‌شود. بخوانید System::String."
type: docs
weight: 27
url: /fa/aspose.slides/loadoptions/get_defaultregularfont/
---
## متد LoadOptions::get_DefaultRegularFont()

در صورتی که فونت منبع یافت نشود، فونت Regular استفاده می‌شود. بخوانید [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## توضیحات

مثال زیر نشان می‌دهد چگونه فونت‌های پیش‌فرض را برای رندر کردن PowerPoint [Presentation](../../presentation/) تنظیم کنیم.
```cpp
// از گزینه‌های بارگذاری برای تعیین فونت‌های پیش‌فرض regular و asian استفاده کنید
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// بارگذاری ارائه
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// تولید تصویر بندانگشتی اسلاید
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// تولید PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// تولید XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [LoadOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)