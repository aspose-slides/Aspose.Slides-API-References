---
title: get_Character()
second_title: مرجع API Aspose.Slides للغة C++
description: "حرف التشكيل يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF) القيمة الافتراضية: التشكيل القوسي المتجمع (U+0302)"
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() طريقة

حرف التشكيل يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF) القيمة الافتراضية: التشكيل المتجمع القوسي (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## ملاحظات

مثال:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## انظر أيضًا

* الفئة [MathAccent](../)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)