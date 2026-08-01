---
title: MathSuperscriptElement()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de MathSuperscriptElement klasse.
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/mathsuperscriptelement/mathsuperscriptelement/
---
## MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


Initialiseert een nieuw exemplaar van de [MathSuperscriptElement](../) klasse.

```cpp
Aspose::Slides::MathText::MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> superScript)
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathSuperscriptElement](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)