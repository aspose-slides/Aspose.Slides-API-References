---
title: get_Operator()
second_title: Aspose.Slides für C++ API-Referenz
description: "Nary-Operator-Zeichen Zum Beispiel: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /de/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() Methode


Nary-Operator-Zeichen Zum Beispiel: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Anmerkungen


Beispiel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Siehe auch

* Klasse [MathNaryOperator](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)