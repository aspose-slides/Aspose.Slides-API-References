---
title: get_Character()
second_title: Aspose.Slides برای C++ مرجع API
description: "اکسنت کاراکتر مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد. مقدار پیش‌فرض: ترکیب سرقوس (U+0302)"
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() متد

اکسنت کاراکتر مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد. مقدار پیش‌فرض: اکسنت ترکیبی سرقوس (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## توضیحات


مثال: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## موارد مرتبط

* کلاس [MathAccent](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)