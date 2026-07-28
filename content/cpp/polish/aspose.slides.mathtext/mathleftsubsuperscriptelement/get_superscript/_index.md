---
title: get_Superscript()
second_title: Aspose.Slides dla C++ - referencja API
description: Indeks górny
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_superscript/
---
## MathLeftSubSuperscriptElement::get_Superscript() metoda


Superscript

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Superscript() override
```

## Uwagi


Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathLeftSubSuperscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)