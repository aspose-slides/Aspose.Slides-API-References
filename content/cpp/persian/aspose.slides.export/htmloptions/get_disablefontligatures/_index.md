---
title: get_DisableFontLigatures()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی به true تنظیم شود، لیگچرها در خروجی رندر غیرفعال می‌شوند. به‌صورت پیش‌فرض، این ویژگی روی false تنظیم شده است.
type: docs
weight: 92
url: /fa/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() متد


یک مقدار را دریافت می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. هنگامی که به **true** تنظیم شود، لیگچرها در خروجی رندر غیرفعال خواهند شد. به‌طور پیش‌فرض، این ویژگی روی **false** تنظیم شده است.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // غیرفعال‌سازی لیگچرها در رندر متن

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## مراجع

* کلاس [HtmlOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)