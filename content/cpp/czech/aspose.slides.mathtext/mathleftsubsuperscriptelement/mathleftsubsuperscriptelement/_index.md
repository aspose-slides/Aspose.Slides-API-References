---
title: MathLeftSubSuperscriptElement()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Inicializuje novou instanci třídy MathLeftSubSuperscriptElement.
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/mathleftsubsuperscriptelement/mathleftsubsuperscriptelement/
---
## MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) konstruktor

Inicializuje novou instanci třídy [MathLeftSubSuperscriptElement](../).

```cpp
Aspose::Slides::MathText::MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript, System::SharedPtr<IMathElement> superScript)
```

## Poznámky


Příklad:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathLeftSubSuperscriptElement](../)
* Obor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)