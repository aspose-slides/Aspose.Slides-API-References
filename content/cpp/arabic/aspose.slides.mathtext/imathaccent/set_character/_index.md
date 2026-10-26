---
title: set_Character()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "حرف التشكيل يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF) القيمة الافتراضية: علامة الجمع المنحدرة (U+0302)"
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) طريقة

حرف التكييف يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF) القيمة الافتراضية: علامة الجمع المخروطية (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## ملاحظات

مثال:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## انظر أيضًا

* فئة [IMathAccent](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)