---
title: get_AlignmentPoint()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: "عند التعيين إلى true، يعمل محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاكاتها معه. القيمة الافتراضية: false"
type: docs
weight: 92
url: /ar/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## طريقة MathBox::get_AlignmentPoint()

When true، يعمل هذا المحاكي للمشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاكاتها معه. القيمة الافتراضية: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## ملاحظات

مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## انظر أيضًا

* فئة [MathBox](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)