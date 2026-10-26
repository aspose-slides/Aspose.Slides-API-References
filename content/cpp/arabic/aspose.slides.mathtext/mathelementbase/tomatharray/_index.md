---
title: ToMathArray()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضع في مصفوفة عمودية
type: docs
weight: 170
url: /ar/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## طريقة MathElementBase::ToMathArray()


يضع في مصفوفة عمودية

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### قيمة الإرجاع

مثيل جديد من النوع [IMathArray](../../imatharray/)
## ملاحظات



مثال: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathArray](../../imatharray/)
* فئة [MathElementBase](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)