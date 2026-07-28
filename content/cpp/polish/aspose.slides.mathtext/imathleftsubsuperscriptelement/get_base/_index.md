---
title: get_Base()
second_title: Aspose.Slides dla C++ – referencja API
description: Argument bazowy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_base/
---
## IMathLeftSubSuperscriptElement::get_Base() metoda


Argument bazowy

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Base()=0
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
* Klasa [IMathLeftSubSuperscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)