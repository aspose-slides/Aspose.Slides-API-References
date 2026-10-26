---
title: Accent()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط علامة تشكيل (حرف على أعلى هذا العنصر)
type: docs
weight: 209
url: /ar/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) طريقة

يضبط علامة تشكيل (حرف على أعلى هذا العنصر)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### الوسائط

| معلمة | نوع | وصف |
| --- | --- | --- |
| accentCharacter | char16_t | حرف التشكيل. يجب أن تكون القيمة ضمن النطاق (U+0300\u2013U+036F) أو (U+20D0\u2013U+20EF) |

### قيمة الإرجاع

مثيل جديد من النوع [IMathAccent](../../imathaccent/)
## ملاحظات



مثال: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathAccent](../../imathaccent/)
* فئة [IMathElement](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)