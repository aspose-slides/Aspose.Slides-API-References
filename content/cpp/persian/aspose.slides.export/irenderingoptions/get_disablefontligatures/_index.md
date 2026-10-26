---
title: get_DisableFontLigatures()
second_title: مرجع API Aspose.Slides برای C++
description: یک مقدار را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض، این ویژگی به false تنظیم شده است.
type: docs
weight: 40
url: /fa/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() متد


یک مقدار را که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود، دریافت می‌کند. هنگامی که به **true** تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به‌صورت پیش‌فرض، این ویژگی به **false** تنظیم شده است.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
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

* کلاس [IRenderingOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)