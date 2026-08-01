---
title: get_Superscript()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert een superscriptargument dat bijvoorbeeld, in het geval van een integraal, de bovengrens instelt
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMMathNaryOperator::get_Superscript() methode

Specificeert een superscriptargument dat bijvoorbeeld, in het geval van een integraal, de bovengrens instelt

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)