---
title: set_Character()
second_title: مرجع API Aspose.Slides لـ C++
description: "حرف التشكيل يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو(U+20D0\\u2013U+20EF) القيمة الافتراضية: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) طريقة

حرف التشكيل يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF) القيمة الافتراضية: Combining Circumflex Accent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## ملاحظات

مثال:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## انظر أيضًا

* فئة [MathAccent](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)