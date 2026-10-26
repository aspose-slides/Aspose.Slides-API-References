---
title: get_Degree()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: معامل الدرجة
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() طريقة

معامل الدرجة

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## ملاحظات

مثال:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // جذر مكعب
auto degreeElem = radical->get_Degree();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathRadical](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)