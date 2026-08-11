---
title: get_Subscript()
second_title: مرجع API Aspose.Slides للـ C++
description: المؤشر السفلي
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathsubscriptelement/get_subscript/
---
## MathSubscriptElement::get_Subscript() طريقة


المؤشر السفلي

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSubscriptElement::get_Subscript() override
```

## ملاحظات


مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathSubscriptElement](../)
* نطاق [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)