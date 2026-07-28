---
title: MathSubscriptElement()
second_title: Aspose.Slides dla interfejsu API C++
description: Inicjalizuje nową instancję klasy MathSubscriptElement.
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/mathsubscriptelement/mathsubscriptelement/
---
## MathSubscriptElement::MathSubscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) konstruktor


Inicjalizuje nową instancję klasy [MathSubscriptElement](../).

```cpp
Aspose::Slides::MathText::MathSubscriptElement::MathSubscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript)
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathSubscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)