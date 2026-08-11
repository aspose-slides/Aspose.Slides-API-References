---
title: get_Character()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: "حرف التشكيل يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF) القيمة الافتراضية: العلامة المركبة للقبعة (U+0302)"
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() طريقة

حرف التشكيل يجب أن تكون القيمة ضمن النطاق (U+0300\u2013U+036F) أو(U+20D0\u2013U+20EF) القيمة الافتراضية: العلامة المركبة للقبعة (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
```

## ملاحظات

مثال:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## راجع أيضًا

* الفئة [IMathAccent](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)