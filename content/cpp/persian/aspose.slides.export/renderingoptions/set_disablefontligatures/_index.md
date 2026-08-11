---
title: set_DisableFontLigatures()
second_title: راهنمای API Aspose.Slides برای C++
description: یک مقدار تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی به false تنظیم شده است.
type: docs
weight: 53
url: /fa/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) متد


یک مقدار تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. وقتی به **true** تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی به **false** تنظیم شده است.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
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

## موارد مرتبط

* کلاس [RenderingOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)