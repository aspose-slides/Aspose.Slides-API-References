---
title: get_Subscript()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δείκτης
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathsubscriptelement/get_subscript/
---
## IMMathSubscriptElement::get_Subscript() μέθοδος


Subscript

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Subscript()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathSubscriptElement](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)