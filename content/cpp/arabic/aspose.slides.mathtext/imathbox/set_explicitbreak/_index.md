---
title: set_ExplicitBreak()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: "الفاصل الصريح يحدد ما إذا كان هناك كسر سطر في بداية كائن Box، بحيث يلتف السطر عند بداية كائن Box. يحدد عدد المشغل في السطر السابق من النص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255. الافتراضي: 0 (بدون فاصل صريح)"
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) طريقة

الفاصل الصريح يحدد ما إذا كان هناك كسر سطر في بداية كائن Box، بحيث يلتف السطر عند بداية كائن Box. يحدد عدد المشغل في السطر السابق من النص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 الافتراضي: 0 (بدون فاصل صريح)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## ملاحظات

مثال:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## انظر أيضًا

* فئة [IMathBox](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)