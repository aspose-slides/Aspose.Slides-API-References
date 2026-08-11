---
title: get_Subscript()
second_title: مرجع API Aspose.Slides للغة C++
description: مؤشر فرعي
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathsubscriptelement/get_subscript/
---
## IMathSubscriptElement::get_Subscript() طريقة

المؤشر الفرعي

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Subscript()=0
```

## ملاحظات

مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathSubscriptElement](../)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)