---
title: ToMathArray()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضع في مصفوفة عمودية
type: docs
weight: 183
url: /ar/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() طريقة


يضع في مصفوفة عمودية

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### قيمة الإرجاع

مثيل جديد من النوع [IMathArray](../../imatharray/)
## ملاحظات



مثال: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathArray](../../imatharray/)
* فئة [IMathElement](../)
* مساحة أسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)