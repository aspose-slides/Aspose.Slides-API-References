---
title: get_DisableFontLigatures()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. وقتی به true تنظیم شود، لیگچرها در خروجی رندر غیرفعال خواهند شد. به طور پیش‌فرض، این ویژگی به false تنظیم می‌شود.
type: docs
weight: 40
url: /fa/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() متد

یک مقدار دریافت می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. وقتی به **true** تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این ویژگی به **false** تنظیم می‌شود.

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // غیرفعال کردن لیگچرها در رندر متن

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## مراجع

* کلاس [RenderingOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)