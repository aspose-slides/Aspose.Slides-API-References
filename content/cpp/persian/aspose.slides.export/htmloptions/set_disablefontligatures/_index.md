---
title: set_DisableFontLigatures()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا خیر. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی روی false تنظیم شده است.
type: docs
weight: 105
url: /fa/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) متد


مقداری را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا خیر. وقتی به **true** تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این خصوصیت روی **false** تنظیم شده است.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## یادداشت‌ها


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // لیگچرها را در رندر متن غیرفعال کنید

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## همچنین ببینید

* کلاس [HtmlOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)