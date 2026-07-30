---
title: set_Operator()
second_title: Riferimento API di Aspose.Slides per C++
description: "Carattere dell'operatore N-ario Per esempio: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) metodo

Carattere dell'operatore N-ario Per esempio: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## Osservazioni


Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Vedi anche

* Classe [IMathNaryOperatorProperties](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)