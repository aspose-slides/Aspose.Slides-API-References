---
title: get_Superscript()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Superskrypt
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathsuperscriptelement/get_superscript/
---
## IMathSuperscriptElement::get_Superscript() metoda


Superskrypt

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSuperscriptElement::get_Superscript()=0
```

## Uwagi


Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto super = superscriptElement->get_Superscript();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathSuperscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)