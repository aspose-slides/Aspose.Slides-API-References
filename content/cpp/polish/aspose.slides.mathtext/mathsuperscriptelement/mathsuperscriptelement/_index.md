---
title: MathSuperscriptElement()
second_title: Aspose.Slides dla C++ Referencja API
description: Inicjalizuje nową instancję klasy MathSuperscriptElement.
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/mathsuperscriptelement/mathsuperscriptelement/
---
## MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) konstruktor


Inicjalizuje nową instancję klasy [MathSuperscriptElement](../).

```cpp
Aspose::Slides::MathText::MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> superScript)
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathSuperscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)