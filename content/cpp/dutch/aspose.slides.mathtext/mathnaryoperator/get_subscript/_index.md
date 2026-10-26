---
title: get_Subscript()
second_title: Aspose.Slides voor C++ API Referentie
description: Bepaalt een subscriptargument dat, bijvoorbeeld in het geval van een integraal, de ondergrens instelt
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() methode

Bepaalt een subscriptargument dat, bijvoorbeeld in het geval van een integraal, de ondergrens instelt

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
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
* Klasse [MathNaryOperator](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)