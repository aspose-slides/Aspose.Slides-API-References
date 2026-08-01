---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Base-argument
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_base/
---
## IMathLeftSubSuperscriptElement::get_Base() methode


Base-argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Base()=0
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
* Klasse [IMathLeftSubSuperscriptElement](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)