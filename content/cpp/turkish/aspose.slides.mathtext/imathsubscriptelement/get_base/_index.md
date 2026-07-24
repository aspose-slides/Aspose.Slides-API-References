---
title: get_Base()
second_title: Aspose.Slides için C++ API Referansı
description: Base argüman
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathsubscriptelement/get_base/
---
## IMathSubscriptElement::get_Base() metod

Base argüman

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Base()=0
```

## Açıklamalar

Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto baseElem = subscriptElement->get_Base();
```

## Ayrıca Bakınız

* typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathSubscriptElement](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)