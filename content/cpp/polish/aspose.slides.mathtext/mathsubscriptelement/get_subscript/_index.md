---
title: get_Subscript()
second_title: Aspose.Slides dla C++ – Odniesienie API
description: Indeks dolny
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathsubscriptelement/get_subscript/
---
## MathSubscriptElement::get_Subscript() metoda


Subscript

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSubscriptElement::get_Subscript() override
```

## Uwagi


Przykład:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathSubscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)