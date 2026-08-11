---
title: get_SpellCheck()
second_title: مرجع API Aspose.Slides برای C++
description: مقداری را برمی‌گرداند که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی‌های املا برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض false است.
type: docs
weight: 599
url: /fa/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() متد

دریافت مقداری که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی روی false تنظیم شود، بررسی املا برای عناصر متن سرکوب می‌شود. وقتی روی true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## توضیحات

مثال بعدی نشان می‌دهد که چگونه قبل از ذخیره‌سازی ارائه، پرچم SpellCheck فعال می‌شود: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// دسترسی به اولین قسمت متن داخل اولین شکل در اولین اسلاید
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// فعال‌سازی بررسی املایی برای این قسمت متن
portion->get_PortionFormat()->set_SpellCheck(true);
// ذخیره ارائه‌ی تغییر یافته
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## مراجع

* کلاس [IBasePortionFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)