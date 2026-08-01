---
title: get_Base()
second_title: Aspose.Slides for C++ API-referentie
description: Base-argument
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_base/
---
## MathLeftSubSuperscriptElement::get_Base() methode


Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Base() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = leftSubSuperscript->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathLeftSubSuperscriptElement](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)