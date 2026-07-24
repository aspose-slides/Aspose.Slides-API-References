---
title: set_Operator()
second_title: Aspose.Slides für C++ API-Referenz
description: "Nary-Operatorzeichen Zum Beispiel: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) Methode


Nary-Operatorzeichen Zum Beispiel: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## Bemerkungen


Beispiel:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Siehe auch

* Klasse [IMathNaryOperatorProperties](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)