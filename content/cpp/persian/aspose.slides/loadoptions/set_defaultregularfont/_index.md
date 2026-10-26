---
title: set_DefaultRegularFont()
second_title: Aspose.Slides برای C++ مرجع API
description: "فونت Regular را تنظیم می‌کند که در صورت عدم یافتن فونت منبع استفاده می‌شود. بنویسید System::String."
type: docs
weight: 40
url: /fa/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) متد


فونت Regular را تنظیم می‌کند که در صورت عدم یافتن فونت منبع استفاده می‌شود. نویسید [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## توضیحات


مثال زیر نشان می‌دهد که چگونه فونت‌های پیش‌فرض را برای رندر کردن PowerPoint [Presentation](../../presentation/) تنظیم کنید. 
```cpp
// از گزینه‌های بارگذاری برای تعریف فونت‌های پیش‌فرض regular و asian استفاده کنید
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
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)