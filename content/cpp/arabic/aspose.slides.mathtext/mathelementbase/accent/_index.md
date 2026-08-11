---
title: Accent()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضبط علامة تشكيل (حرف في أعلى هذا العنصر)
type: docs
weight: 196
url: /ar/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) طريقة

يضبط علامة تشكيل (حرف في أعلى هذا العنصر)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| accentCharacter | char16_t | حرف التشكيل. يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF) |

### قيمة الإرجاع

كائن جديد من النوع [IMathAccent](../../imathaccent/)

## ملاحظات

مثال: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathAccent](../../imathaccent/)
* فئة [MathElementBase](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)