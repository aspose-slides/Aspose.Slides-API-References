---
title: get_Subscript()
second_title: Aspose.Slides för C++ API-referens
description: Nedsänkt
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathsubscriptelement/get_subscript/
---
## IMathSubscriptElement::get_Subscript() metod

Nedsänkt

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Subscript()=0
```

## Anmärkningar

Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathSubscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)