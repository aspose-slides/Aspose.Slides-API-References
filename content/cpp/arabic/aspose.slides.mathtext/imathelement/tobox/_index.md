---
title: ToBox()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو أي نص رياضي آخر. يمكن أن يكون الكائن المعبأ (على سبيل المثال) محاكيًا لمعامل مع أو بدون نقطة محاذاة، أو نقطة كسر سطر، أو يُجمّع بحيث لا يسمح بحدوث كسر سطر داخلي.
type: docs
weight: 274
url: /ar/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() طريقة

يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يستخدم لتجميع مكونات معادلة أو أي نص رياضي آخر. يمكن أن يكون الصندوق (على سبيل المثال) محاكيًا لمعامل مع أو بدون نقطة محاذاة، أو نقطة كسر سطر، أو يُجمّع بحيث لا تسمح بحدوث كسر سطر داخلية.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```

### قيمة الإرجاع

صندوق منطقي يحتوي على هذا العنصر

## ملاحظات

مثال:
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBox](../../imathbox/)
* فئة [IMathElement](../)
* نطاق [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)