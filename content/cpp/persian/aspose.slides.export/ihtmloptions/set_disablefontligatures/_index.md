---
title: set_DisableFontLigatures()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدارئی تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود یا نه. وقتی به true تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی به false تنظیم شده است.
type: docs
weight: 196
url: /fa/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) متد

یک مقدار تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود یا نه. وقتی به **true** تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این ویژگی به **false** تنظیم شده است.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // غیرفعال کردن لیگاتورها در رندر متن

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## موارد مرتبط

* کلاس [IHtmlOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)