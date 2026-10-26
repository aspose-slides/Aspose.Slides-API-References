---
title: set_ExplicitBreak()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يحدد الكسر الصريح ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يلتف السطر عند بداية كائن الصندوق. يحدد عدد العامل في السطر السابق من النص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 الافتراضي: 0 (بدون كسر صريح)"
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) طريقة

تحدد الكسر الصريح ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يلتف السطر عند بداية كائن Box. تحدد عدد العامل في السطر السابق من النص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 الافتراضي: 0 (بدون كسر صريح)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## ملاحظات

مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## انظر أيضًا

* فئة [MathBox](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)