---
title: get_SpellCheck()
second_title: Aspose.Slides برای مرجع API C++
description: یک مقدار را برمی‌گرداند که نشان می‌دهد آیا بررسی املا برای بخش متن فعال است یا نه. وقتی این ویژگی بر روی false تنظیم شود، بررسی املا برای عناصر متن سرکوب می‌شود. وقتی بر روی true تنظیم شود، بررسی املا مجاز است. مقدار پیش‌فرض false است.
type: docs
weight: 599
url: /fa/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() متد


یک مقدار را برمی‌گرداند که نشان می‌دهد آیا بررسی املا برای بخش متن فعال است یا نه. وقتی این ویژگی بر روی false تنظیم شود، بررسی املا برای عناصر متن سرکوب می‌شود. وقتی بر روی true تنظیم شود، بررسی املا مجاز است. مقدار پیش‌فرض **false** است.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## توضیحات


مثال بعدی نشان می‌دهد که چگونه پرچم SpellCheck را قبل از ذخیره ارائه فعال می‌کنیم:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// دسترسی به اولین بخش متن داخل اولین شکل در اولین اسلاید
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// فعال‌سازی بررسی املا برای این بخش متن
portion->get_PortionFormat()->set_SpellCheck(true);
// ذخیرهٔ ارائهٔ تغییر یافته
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [BasePortionFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)