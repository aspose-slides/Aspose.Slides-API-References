---
title: get_Superscript()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert een superscriptargument dat bijvoorbeeld, in het geval van een integraal, de bovengrens instelt
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() methode


Specificeert een superscriptargument dat bijvoorbeeld, in het geval van een integraal, de bovengrens instelt

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
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
* Klasse [MathNaryOperator](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)