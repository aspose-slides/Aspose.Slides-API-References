---
title: set_Operator()
second_title: Aspose.Slides für C++ API Referenz
description: "Nary Operator Zeichen Zum Beispiel: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /de/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) Methode


Nary Operator Character Zum Beispiel: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Hinweise


Beispiel:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Siehe auch

* Klasse [MathNaryOperator](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)