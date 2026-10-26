---
title: set_Character()
second_title: مرجع API Aspose.Slides برای C++
description: "کاراکتر اکسنت مقدار باید در بازهٔ (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: ترکیب سرکل اکسنت (U+0302)"
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) متد


کاراکتر اکسنت مقدار باید در بازهٔ (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: اکسنت ترکیبی سرکل (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## توضیحات


مثال: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## مراجع

* کلاس [MathAccent](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)