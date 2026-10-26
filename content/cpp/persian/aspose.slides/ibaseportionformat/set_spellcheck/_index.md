---
title: set_SpellCheck()
second_title: مرجع API Aspose.Slides برای C++
description: یک مقدار تنظیم می‌کند که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا نه. وقتی این ویژگی روی false تنظیم شود، بررسی‌های املایی برای عناصر متن سرکوب می‌شوند. وقتی روی true تنظیم شود، اجازهٔ بررسی املایی داده می‌شود. مقدار پیش‌فرض false است.
type: docs
weight: 612
url: /fa/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) متد


یک مقدار تنظیم می‌کند که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی روی false تنظیم شود، بررسی‌های املایی برای عناصر متن سرکوب می‌شوند. وقتی روی true تنظیم شود، اجازهٔ بررسی املایی داده می‌شود. مقدار پیش‌فرض **false** است.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## توضیحات


مثال بعدی نشان می‌دهد که چگونه پرچم SpellCheck را قبل از ذخیرهٔ ارائه فعال می‌کنیم: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// دسترسی به اولین بخش متن داخل اولین شکل در اولین اسلاید
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// فعال کردن بررسی املایی برای این بخش متن
portion->get_PortionFormat()->set_SpellCheck(true);
// ذخیرهٔ ارائهٔ اصلاح‌شده
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## مراجع

* کلاس [IBasePortionFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)