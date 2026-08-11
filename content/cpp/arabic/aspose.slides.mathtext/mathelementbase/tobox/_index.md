---
title: ToBox()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكونات معادلة أو أي نص رياضي آخر. يمكن لكائن الصندوق (على سبيل المثال) أن يعمل كمحاكي للمشغل مع أو بدون نقطة محاذاة، أو أن يكون نقطة كسر سطر، أو أن يُجمع بحيث لا يُسمح بوجود فواصل أسطر داخله.
type: docs
weight: 261
url: /ar/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() طريقة

يقوم بوضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) يُستخدم لتجميع مكوّنات معادلة أو أي نص رياضي آخر. يمكن لكائن صندوق (على سبيل المثال) أن يعمل كمحاكي للمشغل مع أو بدون نقطة محاذاة، أو أن يكون نقطة كسر سطر، أو أن يُجمع بحيث لا يسمح بوجود فواصل أسطر داخله.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```

### قيمة الإرجاع

صندوق منطقي يحتوي على هذا العنصر داخل

## ملاحظات

مثال:
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBox](../../imathbox/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)