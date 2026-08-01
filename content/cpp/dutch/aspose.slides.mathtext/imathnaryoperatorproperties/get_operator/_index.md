---
title: get_Operator()
second_title: Aspose.Slides voor C++ API-referentie
description: "Nary-operator teken Bijvoorbeeld: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() methode


Nary-operator teken Bijvoorbeeld: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Zie ook

* Klasse [IMathNaryOperatorProperties](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)