---
title: get_Base()
second_title: Aspose.Slides dla C++ – Referencja API
description: Argument bazowy
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathsuperscriptelement/get_base/
---
## MathSuperscriptElement::get_Base() metoda


argument Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Base() override
```

## Uwagi


Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto baseElem = superscriptElement->get_Base();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathSuperscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)