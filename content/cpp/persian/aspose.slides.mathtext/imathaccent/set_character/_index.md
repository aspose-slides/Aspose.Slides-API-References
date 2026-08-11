---
title: set_Character()
second_title: مرجع API Aspose.Slides برای C++
description: "کاراکتر لهجه مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد. مقدار پیش‌فرض: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/imathaccent/set_character/
---
## IMMathAccent::set_Character(char16_t) متد


کاراکتر لهجه مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد. مقدار پیش‌فرض: Combining Circumflex Accent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## توضیح


مثال: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## مراجع

* کلاس [IMathAccent](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)