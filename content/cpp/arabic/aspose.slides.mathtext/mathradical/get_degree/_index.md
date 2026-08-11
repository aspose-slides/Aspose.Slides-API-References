---
title: get_Degree()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: معامل الدرجة
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() طريقة

معامل الدرجة

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## ملاحظات

مثال: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathRadical](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)