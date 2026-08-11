---
title: set_AlignmentPoint()
second_title: مرجع API Aspose.Slides لـ C++
description: "عند تعيينه إلى true، يعمل محاكي هذا المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. الافتراضي: false"
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/imathbox/set_alignmentpoint/
---
## IMathBox::set_AlignmentPoint(bool) طريقة

عند تعيينه إلى true، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. الافتراضي: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_AlignmentPoint(bool value)=0
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