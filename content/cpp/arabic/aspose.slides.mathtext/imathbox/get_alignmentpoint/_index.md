---
title: get_AlignmentPoint()
second_title: "مرجع API لـ Aspose.Slides للغة C++"
description: "عند القيمة true، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. القيمة الافتراضية: false"
type: docs
weight: 92
url: /ar/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() طريقة

عند القيمة true، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. الافتراضي: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## ملاحظات

مثال:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## انظر أيضًا

* الفئة [IMathBox](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)