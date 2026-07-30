---
title: get_Subscript()
second_title: Riferimento API di Aspose.Slides per C++
description: Pedice
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathsubscriptelement/get_subscript/
---
## MathSubscriptElement::get_Subscript() method

Subscript

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSubscriptElement::get_Subscript() override
```

## Osservazioni

Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathSubscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)