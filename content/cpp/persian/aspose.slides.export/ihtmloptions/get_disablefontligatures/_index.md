---
title: get_DisableFontLigatures()
second_title: مرجع API Aspose.Slides برای C++
description: یک مقدار را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود. وقتی به true تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی روی false تنظیم شده است.
type: docs
weight: 183
url: /fa/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() متد

یک مقدار را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود یا نه. وقتی به **true** تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌گردند. به طور پیش‌فرض، این ویژگی روی **false** تنظیم شده است.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // در رندر متن لیگاتورها را غیرفعال کنید

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## موارد مرتبط

* کلاس [IHtmlOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)