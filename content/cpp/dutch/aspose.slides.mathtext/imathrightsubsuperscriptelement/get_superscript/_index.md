---
title: get_Superscript()
second_title: Aspose.Slides voor C++ API Referentie
description: Superscript-argument
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_superscript/
---
## IMathRightSubSuperscriptElement::get_Superscript() methode

Superscript argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Superscript()=0
```

## Opmerkingen

Voorbeeld:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = subsuperscript->get_Superscript();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathRightSubSuperscriptElement](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)