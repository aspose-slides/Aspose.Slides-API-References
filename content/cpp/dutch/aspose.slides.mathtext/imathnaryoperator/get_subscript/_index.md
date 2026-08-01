---
title: get_Subscript()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert een subscriptargument dat bijvoorbeeld, in het geval van een integraal, de ondergrens instelt
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() method

Specificeert een subscriptargument dat bijvoorbeeld, in het geval van een integraal, de ondergrens instelt

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathNaryOperator](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)