---
title: ToMathArray()
second_title: Aspose.Slides لمرجع API C++
description: يضع العناصر الفرعية في مصفوفة عمودية
type: docs
weight: 235
url: /ar/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() طريقة

يضع العناصر الفرعية في مصفوفة عمودية

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```

### قيمة الإرجاع

مثيل جديد من النوع [IMathArray](../../imatharray/)
## ملاحظات

مثال:
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathArray](../../imatharray/)
* فئة [MathBlock](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)