---
title: get_Subscript()
second_title: Aspose.Slides for C++ API Referansı
description: Alt Simge
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathsubscriptelement/get_subscript/
---
## IMathSubscriptElement::get_Subscript() metot

Alt Simge

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Subscript()=0
```

## Açıklamalar

Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathSubscriptElement](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)