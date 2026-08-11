---
title: set_DisableFontLigatures()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا خیر. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این خصوصیت به false تنظیم شده است.
type: docs
weight: 53
url: /fa/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) متد


یک مقدار تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا خیر. وقتی به **true** تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این خصوصیت به **false** تنظیم شده است.

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
```

## ملاحظات


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