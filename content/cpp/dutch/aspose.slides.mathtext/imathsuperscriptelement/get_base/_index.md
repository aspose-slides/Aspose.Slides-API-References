---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Basisargument
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathsuperscriptelement/get_base/
---
## IMathSuperscriptElement::get_Base() methode


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSuperscriptElement::get_Base()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto baseElem = superscriptElement->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathSuperscriptElement](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)