---
title: get_Base()
second_title: Aspose.Slides لتوثيق API لـ C++
description: معامل Base
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathsubscriptelement/get_base/
---
## IMathSubscriptElement::get_Base() طريقة


معامل Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Base()=0
```

## ملاحظات


مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto baseElem = subscriptElement->get_Base();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathSubscriptElement](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)