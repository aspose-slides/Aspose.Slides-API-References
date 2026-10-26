---
title: get_ExplicitBreak()
second_title: مرجع API Aspose.Slides للـ C++
description: "الفاصل الصريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يلتف السطر في بداية كائن Box. يحدد عدد الـ operator في السطر السابق من النص الرياضي والذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 القيمة الافتراضية: 0 (لا فاصل صريح)"
type: docs
weight: 118
url: /ar/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() طريقة

يحدد الفاصل الصريح ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يلتف السطر في بداية كائن Box. يحدد عدد الـ operator في السطر السابق من النص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 القيمة الافتراضية: 0 (لا فاصل صريح)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## ملاحظات

مثال:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## انظر أيضًا

* الفئة [MathBox](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)