---
title: Accent()
second_title: Aspose.Slides برای C++ مرجع API
description: یک علامت تاکید (کاراکتری در بالای این عنصر) را تنظیم می‌کند
type: docs
weight: 196
url: /fa/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) متد

یک علامت تاکید (کاراکتر در بالای این عنصر) را تنظیم می‌کند

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| accentCharacter | char16_t | کاراکتر تاکید. مقدار باید در بازهٔ (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد |

### مقدار بازگشت

نمونهٔ جدید از نوع [IMathAccent](../../imathaccent/)
## توضیحات



مثال: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## مراجعه

* نوع‌تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathAccent](../../imathaccent/)
* کلاس [MathElementBase](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)