---
title: get_Base()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Argument bazowy
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_base/
---
## MathLeftSubSuperscriptElement::get_Base() metoda


argument bazowy

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Base() override
```

## Uwagi


Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = leftSubSuperscript->get_Base();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathLeftSubSuperscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)