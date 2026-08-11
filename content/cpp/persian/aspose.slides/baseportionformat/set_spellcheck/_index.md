---
title: set_SpellCheck()
second_title: Aspose.Slides برای مرجع API C++
description: یک مقدار تنظیم می‌کند که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی روی false تنظیم می‌شود، بررسی‌های املایی برای عناصر متن سرکوب می‌شوند. وقتی روی true تنظیم می‌شود، اجازه بررسی املایی داده می‌شود. مقدار پیش‌فرض false است.
type: docs
weight: 612
url: /fa/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) متد

یک مقدار تنظیم می‌کند که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی روی false تنظیم شود، بررسی‌های املایی برای عناصر متن سرکوب می‌شوند. وقتی روی true تنظیم شود، اجازه بررسی املایی داده می‌شود. مقدار پیش‌فرض **false** است.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## توضیحات

مثال بعدی نشان می‌دهد که چگونه پرچم SpellCheck قبل از ذخیره‌سازی ارائه فعال می‌شود:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// دسترسی به اولین بخش متن داخل اولین شکل در اولین اسلاید
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// فعال‌سازی بررسی املایی برای این بخش متن
portion->get_PortionFormat()->set_SpellCheck(true);
// ذخیره ارائهٔ تغییر یافته
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [BasePortionFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)