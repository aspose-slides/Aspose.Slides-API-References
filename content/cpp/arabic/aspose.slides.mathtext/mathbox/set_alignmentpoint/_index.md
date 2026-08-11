---
title: set_AlignmentPoint()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "عند القيمة true، يعمل محاكي العامل هذا كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. القيمة الافتراضية: false"
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/mathbox/set_alignmentpoint/
---
## MathBox::set_AlignmentPoint(bool) طريقة

عند القيمة true، يعمل محاكي العامل هذا كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. القيمة الافتراضية: false

```cpp
void Aspose::Slides::MathText::MathBox::set_AlignmentPoint(bool value) override
```

## ملاحظات

مثال:

```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## انظر أيضًا

* الفئة [MathBox](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)