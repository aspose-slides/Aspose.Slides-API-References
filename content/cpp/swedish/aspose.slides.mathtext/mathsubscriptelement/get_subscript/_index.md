---
title: get_Subscript()
second_title: Aspose.Slides för C++ API-referens
description: Nedsänkt
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathsubscriptelement/get_subscript/
---
## MathSubscriptElement::get_Subscript() metod


Nedsänkt

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSubscriptElement::get_Subscript() override
```

## Anmärkningar


Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathSubscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)