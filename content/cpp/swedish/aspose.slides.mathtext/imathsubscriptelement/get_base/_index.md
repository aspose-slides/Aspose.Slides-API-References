---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Basargument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathsubscriptelement/get_base/
---
## IMathSubscriptElement::get_Base() metod

Basargument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Base()=0
```

## Anmärkningar

Exempel:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto baseElem = subscriptElement->get_Base();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathSubscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)