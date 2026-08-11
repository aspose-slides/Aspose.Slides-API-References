---
title: get_Character()
second_title: مستندات API Aspose.Slides برای C++
description: "کاراکتر لهجه مقدار باید در بازهٔ (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: ترکیب اکسنت گرد (U+0302)"
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() متد

Accent Character کاراکتر لهجه مقدار باید در بازهٔ (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد Default value: مقدار پیش‌فرض: ترکیب اکسنت گرد (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
```

## توضیحات

مثال:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## موارد مرتبط

* کلاس [IMathAccent](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)