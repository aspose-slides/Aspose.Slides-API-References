---
title: set_Operator()
second_title: Aspose.Slides voor C++ API-referentie
description: "Nary-operator teken Bijvoorbeeld: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) methode


Nary-operator teken Bijvoorbeeld: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Zie ook

* Klasse [MathNaryOperator](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)