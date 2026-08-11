---
title: get_ExplicitBreak()
second_title: مرجع API Aspose.Slides للـ C++
description: "تحدد الخاصية Explicit break ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يلتف السطر عند بداية كائن الصندوق. تحدد عدد الـ operator في السطر السابق للنص الرياضي والذي سيُستخدم كنقطة محاذاة للسطر الحالي للنص الرياضي. القيم الممكنة: 1..255. الافتراضي: 0 (بدون فاصل صريح)"
type: docs
weight: 118
url: /ar/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() طريقة

يحدد Explicit break ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يلتف السطر عند بداية كائن Box. يحدد عدد الـ operator في السطر السابق للنص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي للنص الرياضي القيم الممكنة: 1..255 الافتراضي: 0 (بدون Explicit break)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
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