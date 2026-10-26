---
title: Accent()
second_title: مرجع API Aspose.Slides برای C++
description: یک علامت لهجه تنظیم می‌کند (کاراکتری در بالای این عنصر)
type: docs
weight: 209
url: /fa/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) متد

یک علامت لهجه تنظیم می‌کند (یک کاراکتر در بالای این عنصر)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| accentCharacter | char16_t | کاراکتر لهجه. مقدار باید در محدودهٔ (U+0300-U+036F) یا (U+20D0-U+20EF) باشد |

### مقدار بازگشتی

نمونهٔ جدیدی از نوع [IMathAccent](../../imathaccent/)

## نکات

مثال: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathAccent](../../imathaccent/)
* کلاس [IMathElement](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)