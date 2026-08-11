---
title: get_Subscript()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: منخفض
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_subscript/
---
## IMathLeftSubSuperscriptElement::get_Subscript() طريقة


منخفض

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Subscript()=0
```

## ملاحظات


مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathLeftSubSuperscriptElement](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)